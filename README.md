Based on the files you provided, here is a `README.md` file for your project:

```markdown
# Web Crawler

A simple web crawler built with Node.js that recursively fetches all the clickable links from a given website and generates a report on the number of links found per page.

## Project Structure

- `main.js`: The entry point of the application. It validates the input URL, initiates the crawling process, and generates a report.
- `crawl.js`: Contains the core functionality of the crawler, including fetching pages, extracting URLs from HTML, and normalizing URLs.
- `report.js`: Responsible for sorting and generating a report of the crawled pages based on the number of links found.
- `crawl.test.js`: Unit tests for the functions in `crawl.js`.
- `report.test.js`: Unit tests for the functions in `report.js`.
- `package.json`: Contains project metadata, dependencies, and scripts.
- `package-lock.json`: Automatically generated and ensures consistency across installs.

## Installation

To install the necessary dependencies, run:

```bash
npm install
```

## Usage

To start the web crawler, run the following command:

```bash
npm start <URL>
```

Replace `<URL>` with the website you want to crawl.

### Example

```bash
npm start https://example.com
```

## Testing

To run the tests, use the following command:

```bash
npm test
```

## Dependencies

- `jsdom`: Used to parse the HTML and extract URLs.
- `jest`: Testing framework for unit tests.

