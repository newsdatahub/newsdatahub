<div align="center">
  <img width="120" height="120" alt="NewsDataHub logo" src="https://github.com/user-attachments/assets/33414a3a-3367-4128-83a7-ff80f088cdb6" />
    <br />
    <a href="https://status.newsdatahub.com">
      <img alt="Status" src="https://img.shields.io/badge/status-status.newsdatahub.com-brightgreen" />
    </a>
    <a href="https://www.postman.com/aviation-operator-7936876/newsdatahub-api/overview">
      <img src="https://run.pstmn.io/button.svg" alt="Run in Postman" />
    </a>
  </div>

  # NewsDataHub API

  Access 200,000+ fresh articles daily from 6,500+ sources across 170+ countries in 40+ languages — enriched with topics,
  source data, and other metadata. Free tier, no card required. Visit our [main website][website] to learn more.

  - Uptime: [status.newsdatahub.com](https://status.newsdatahub.com)
  - Postman: [collection link](https://www.postman.com/aviation-operator-7936876/newsdatahub-api/overview)
  - Subscribe to our <a href="https://newsdatahub.com/newsletter.html">Newsletter</a> for insights, product updates, and behind-the-scenes

  ## Quick Start

  ### Python
  ```python
  import requests

  headers = {
      "X-Api-Key": "your_api_key_here",
      "User-Agent": "YourApp/1.0"
  }

  resp = requests.get("https://api.newsdatahub.com/v1/news", headers=headers)
  print(resp.json())
```

  ### JavaScript
```javascript
  const axios = require("axios");

  const headers = {
    "X-Api-Key": "your_api_key_here",
    "User-Agent": "YourApp/1.0"
  };

  async function getNews() {
    const resp = await axios.get("https://api.newsdatahub.com/v1/news", { headers });
    console.log(resp.data);
  }

  getNews();
```
  ### Curl
```
  curl -H "X-Api-Key: YOUR_API_KEY" -H "User-Agent: yourapp/1.0" \
    "https://api.newsdatahub.com/v1/news?q=technology&per_page=5"
```

<!-- Optionally embed GIFs of the curls above here -->

  ## Features

  - Access 200,000+ fresh articles daily
  - Free tier with 100 daily requests
  - Advanced search with boolean operators and exact phrase matching
  - 40+ languages and 6,500+ sources
  - Rich article metadata and /related for content discovery
  - Simple REST API with standardized JSON

  ## Getting Started

  1. [Sign up](https://newsdatahub.com/login)  for your free API key
  2. Add the key via the X-Api-Key header
  3. Start fetching news data!

  ## Documentation

  See the [API Reference](https://newsdatahub.com/docs) for:

  - Authentication and quotas
  - Pagination
  - Filtering options
  - Code samples in Python, Node.js, Go, and Ruby
