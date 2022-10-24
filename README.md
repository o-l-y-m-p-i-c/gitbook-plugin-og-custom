# gitbook-plugin-open-graph

Adds open graph and twitter sharing meta information to `<head>`

## Installation

    npm install gitbook-plugin-og-custom

## Usage

add to `book.json`

```
{
  "plugins": [
    "og-custom"
  ],
  "pluginsConfig": {
    "open-graph": {
      "baseURL": "http://example.com"
      "defaultDescription": "This is my default share description",
      "defaultImage": "images/default-share.jpg"
    }
  }
}
```
