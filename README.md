# AniX - Stream Animes

This is the backend repository of AniX built with scrapy framework. If you want to visit the frontend repo, [click here](https://github.com/manikandanraji/AniX).

## Spiders

| name                                           | description                  |
| ---------------------------------------------- | ---------------------------- |
| [animes](anix/spiders/animes.py)               | fetch animes                 |
| [anime](anix/spiders/anime.py)                 | fetch a single anime         |
| [search_animes](anix/spiders/search_animes.py) | search animes                |
| [stream](anix/spiders/stream.py)               | fetch mp4 link for a episode |
