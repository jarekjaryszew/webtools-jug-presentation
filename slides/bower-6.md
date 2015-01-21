##  Bower 6

If you need to change bower settings for the project like default package location create .bowerrc file in project root. Example file:

```
{
  "directory": "app/components/",
  "analytics": false,
  "timeout": 120000,
  "registry": {
    "search": [
    "http://localhost:8000",
    "https://bower.herokuapp.com"
    ]
  }
}
```
