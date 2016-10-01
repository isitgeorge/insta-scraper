# insta-scraper
Node.js module for getting basic data from instagram without logging

## Installation
```
soon
```

## Usage
```
var scraper = require('scraper');
```
**insta-scraper** offers these promise methods:
```
scraper.getAccountInfo(username, function(response_json){ })
```

```
scraper.getAccountMedias(username, [max_id], function(response_json){ })
```

```
scraper.getMediasByTag(tag, [max_id], function(response_json){ })
```

```
scraper.getMediasByLocationId(locationId, [max_id], function(response_json){ })
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


