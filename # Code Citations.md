# Code Citations

## License: MIT
https://github.com/oeyoews/tiddlywiki-starter-kit/tree/89ace70d8fd1f1fba4909fe078eafb60429feb86/tiddlers/content/fetch-api.md

```javascript
return response.json();
  })
  .then(data => {
    console.log(data);
  })
  .catch(error => {
    console.error('There was a problem with the fetch operation:', error);
  });