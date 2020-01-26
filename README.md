# ds_salary_h1b
Inspired by this article "How Much Do Data Scientists Make?" I decided to take the same data source and do some analysis in a sligtly different way. 



-----------

### web_scraping
Python Web Scraping Using BeautifulSoup [Tutorial :link:](https://www.dataquest.io/blog/web-scraping-tutorial-python/)
- Usage: usually access web data in csv or API, but sometimes data only accessible as part of a web page
- `get` request: web browser makes a request to a web server since we’re getting files from the server

### html_tags
Tags have commonly used names that depend on their position in relation to other tags:
- `child` — a child is a tag inside another tag. So the two p tags above are both children of the body tag;
- `parent` — a parent is the tag another tag is inside. Above, the html tag is the parent of the body tag;
- `sibiling` — a sibiling is a tag that is nested inside the same parent as another tag. For example, head and body are siblings, since they’re both inside html. Both p tags are siblings, since they’re both inside body;
```html
<html>
    <head>
    </head>
  
    <body>
        <p>
        Here's a paragraph of text!
        </p>
      
        <p>
        Here's a second paragraph of text!
        </p>
    </body>
  
</html>
```
