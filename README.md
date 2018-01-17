# Crawl Instagram Comments

Given some user names, crawl the comments under their posts.

Also dump one representive image of each post.

## Getting Started

### Prerequisites

What things you need to install

```
selenium, beautifulsoup, chrome driver
```

### Installing

* selenium

```
pip install selenium
```

* beautifulsoup

```
conda install beautifulsoup
```

* chrome driver

 See [ChromeDriver - WebDriver for Chrome](https://sites.google.com/a/chromium.org/chromedriver/)

```
Put under somewhere like /usr/bin

Example: /Users/yohuan/anaconda/envs/crawl/bin/chromedriver
```

## Running code

The outputs will be saved under outputs/

```
python crawl_ig_comments.py user1 user2 ...
```

### Example

```
python crawl_ig_comments.py yohuanyang changming8104
```
