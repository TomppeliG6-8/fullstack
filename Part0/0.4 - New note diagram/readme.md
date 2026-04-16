```mermaid
sequenceDiagram
    participant browser
    participant server
#graph TD;
    1-Browser-->HTTP_POST-->https://studies.cs.helsinki.fi/exampleapp/new_note;
    2-https://studies.cs.helsinki.fi/exampleapp/new_note-->302_URL_redirect-->Browser;
    3-Browser-->HTTP_GET-->https://studies.cs.helsinki.fi/exampleapp/notes;
```
HTTP status code 302. This is a URL redirect
