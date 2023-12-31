# Sitemap Generator 🌐

## Project Overview

This Python-based sitemap generator is designed to crawl a website and generate a sitemap in XML format, following the Sitemap Protocol standards.

## Prerequisites

Before using this sitemap generator, make sure you have the following prerequisites installed:

- Python 3
- `requests` library
- `beautifulsoup4` library

You can install the required libraries using pip:

```bash
pip install -r requests.txt
```

## Usage
```bash
python sitemap_generator.py
```

## Code Structure
The project code is organized as follows:

- sitemap_generator.py: Main script for crawling and sitemap generation.
- README.md: Project documentation.
- LICENSE: Project license information.

## Sample Output
Here is an example of a sitemap generated by this tool:

```xml
<?xml version="1.0" encoding="UTF-8"?>
<urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9">
  <url>
    <loc>https://example.com/page1</loc>
  </url>
  <url>
    <loc>https://example.com/page2</loc>
  </url>
</urlset>
```

## License

This project is licensed under the GNU Public License - see the [LICENSE](LICENSE) file for details.


## Author

- [Edgar Gulay](github.com/eddiegulay)
- - ⨉(twitter) [@eddiegulay](https://twitter.com/eddiegulay)

## Conclusion
This sitemap generator simplifies the process of creating sitemaps for websites. We hope you find it useful for your web development projects.
