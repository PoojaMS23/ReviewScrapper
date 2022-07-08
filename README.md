# ReviewScrapper
## A web scraper that collects the reviews of the product from the internet (Here the target is Flipkart). 

### Web scraping is a technique using which the webpages from the internet are fetched and parsed to understand and extract specific information similar to a human being. 

Web scrapping consists of two parts:
-  Web Crawling→ Accessing the webpages over the internet and pulling data from them.
-  HTML Parsing→ Parsing the HTML content of the webpages obtained through web crawling and then extracting specific information from it.
Hence, web scrappers are applications/bots, which automatically send requests to websites and then extract the desired information from the website output.

#### In this project, we’ll take the example of buying a phone online from the flipkart and try to scrap the reviews from the website about the phone that we are planning to buy.

### Project flow:

``` mermaid
  flowchart TD
  a[Start]-->b[User enters keyword to search];
  b -->c[query the DB to check whether the keyword searched is already available in the DB];
  c-->d[reviews found]--yes -->e[show reviews to user];
  d--no-->f[search the internet for reviews]-->g[insert reviews into the database]-->e
```
### Final output:

![image](https://user-images.githubusercontent.com/56773865/178062180-88d05c99-8c22-4451-9421-b2504d96ba71.png)

### Output after search:

![image](https://user-images.githubusercontent.com/56773865/178062365-ec0d7604-9337-4089-b65f-dff16de1b306.png)

## Thank You!
