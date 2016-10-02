# insta-scraper
Node.js module for getting basic data from instagram without login

## Installation
```
soon
```

## Usage
```
var scraper = require('insta-scraper');
```
**insta-scraper** offers these promise methods:
```
scraper.getAccountInfo(username, function(response_json){ })
```

```
scraper.getAccountMedia(username, [max_id], function(response_json){ })
```

```
scraper.getMediaByTag(tag, [max_id], function(response_json){ })
```

```
scraper.getMediaByLocationId(locationId, [max_id], function(response_json){ })
```

```
scraper.getMediaByCode(media_code, function(response_json){ })
```

```
scraper.generalSearch(search_keyword, function(response_json){ })
```

```
scraper.generalQuery(instagram_query, function(response_json){ })
```


