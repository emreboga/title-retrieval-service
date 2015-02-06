# Title Retrieval Service
A REST service based on Node.js to provide a web page title retrieval for a given set of urls.
This is service is currently live on http://title-service.azurewebsites.net/links end-point

### Sample request:
URL: http://title-service.azurewebsites.net/links  
Method: POST  
Body:
```javascript
{
  "links": [
    "http://foo.com"
  ]
}
```
### Sample response:
Response: 
```javascript
{
  "links": [
    {
      "link": "http://foo.com",
      "title": "Foo.com"
    }
  ]
}
```
