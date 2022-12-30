# promo-finder

Script to find recent airline award campaigns in pontospravoar.com.

```
usage: promo-finder [-h] [--title TITLE] [--promo PROMO] {await-promo,search-promos} ...

options:
  -h, --help            show this help message and exit
  --title TITLE         title pattern to be matched
  --promo PROMO         promotion pattern to be matched

Commands:
  {await-promo,search-promos}
    await-promo         Await a matching promo to show up
    search-promos       Search for past promos
```

Uses feedparser to parse RSS feeds, BeautifulSoup4 to parse article
HTMLs, then Pandas to search promotion tables.
