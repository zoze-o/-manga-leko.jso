manga-leko.json
{
  "name": "Manga Leko",
  "version": 1,
  "icon": "https://manga-leko.org/favicon.ico",
  "baseUrl": "https://manga-leko.org",
  "latest": {
    "path": "/latest",
    "method": "GET",
    "mangas": [
      {
        "title": "Example Manga",
        "url": "/example-manga",
        "cover": "https://manga-leko.org/example-cover.jpg"
      }
    ]
  },
  "search": {
    "path": "/search",
    "method": "GET",
    "queryParam": "q",
    "results": [
      {
        "title": "Search Result",
        "url": "/search-result",
        "cover": "https://manga-leko.org/result-cover.jpg"
      }
    ]
  }
}
