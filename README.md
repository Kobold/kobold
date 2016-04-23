
This is my personal site. Don't judge me on this code lol.

To set up for development:

```
❯ mkvirtualenv kobold-github-io
❯ pip install -r requirements.txt
```

And doing things day to day:

```
❯ workon kobold-github-io

# To watch and autorebuild site.
❯ pelican content --autoreload -s pelicanconf.py -t andystheme

# To serve it to localhost:8080
❯ cd output
❯ python -m pelican.server 8080

# To push it live.
❯ fab gh_pages
```
