# Scraper API

This is a Python-based web scraper deployed on Vercel. It scrapes data from a specific URL, parses the HTML, and returns the data as JSON.

## API Endpoints

- **GET /api/list**: Base endpoint with a welcome message.
- **GET /api/list?letter={letter}&page={page}**: Scrapes data for the given letter and page.

### Example
- Request: `/api/list?letter=k&page=1`
- Response:
  ```json
  {
     "data": [
    {
      "duration": "52m",
      "id": "kite-16204",
      "name": "Kite",
      "poster": "https://cdn.noitatnemucod.net/thumbnail/300x400/100/746d993e054e200c4e3148dd90df225c.jpg",
      "title": "Kite",
      "type": "OVA",
      "url": "/watch/kite-16204"
      }
    ]
  }
