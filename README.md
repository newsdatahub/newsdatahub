<div align="center">
  <img width="120" height="120" alt="NewsDataHub logo" src="https://github.com/user-attachments/assets/33414a3a-3367-4128-83a7-ff80f088cdb6" />

</div>

# NewsDataHub API

Access 200,000+ fresh articles daily from 6,500+ unique sources across 170+ countries in 40+ languages — enriched with topics, source and other metadata. Start exploring with our free news API tier - no credit card required.  Visit our [main website][website] to learn more about our service.

## Quick Start

### Python
```python
import requests

headers = {
    'X-Api-Key': 'your_api_key_here',
    'User-Agent': 'YourApp/1.0'
}

response = requests.get('https://api.newsdatahub.com/v1/news', headers=headers)
news_data = response.json()
```

### JavaScript
```javascript
const axios = require('axios');

const headers = {
    'X-Api-Key': 'your_api_key_here',
    'User-Agent': 'YourApp/1.0'
};

async function getNews() {
    try {
        const response = await axios.get('https://api.newsdatahub.com/v1/news', { headers });
        console.log(response.data);
    } catch (error) {
        console.error('Error:', error.message);
    }
}

getNews();
```

## Features

- Access 200,000+ fresh articles daily
- Free tier with 100 daily requests
- Advanced search with boolean operators and exact phrase matching
- Multi-language support across English, Spanish, German, Italian, French and more (40+ languages) 
- Rich article metadata
- Simple REST API with standardized JSON responses
- /related endpoint for content discovery


## Getting Started

1. [Sign up][signup] for your free API key
2. Add the key to your requests using the `X-Api-Key` header
3. Start fetching news data!

## Documentation

Visit our [API Reference][docs] for complete documentation. Our documentation includes detailed information about:
- Authentication
- Pagination
- Result filtering options
- Code samples in Python, Node.js, Go, and Ruby



[website]: https://newsdatahub.com
[signup]: https://newsdatahub.com
[docs]: https://newsdatahub.com/docs
[contact]: mailto:support@newsdatahub.com
