```mermaid
sequenceDiagram
    participant browser
    participant server

    browser->>server: POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa
    activate server


    Note right of browser: Thats it. There is only data gong in to the server. The html page is "updated" locally. There is no need for the server to send data to the browser. 
```
