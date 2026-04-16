```mermaid
graph TD;
    Browser-->HTTP_POST-->https://studies.cs.helsinki.fi/exampleapp/new_note;
    https://studies.cs.helsinki.fi/exampleapp/new_note-->302_URL_redirect-->Browser;
    Browser-->HTTP_GET-->https://studies.cs.helsinki.fi/exampleapp/notes;
```
HTTP status code 302. This is a URL redirect
