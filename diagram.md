```mermaid
sequenceDiagram
    participant browser
    participant server

    browser->>server: POST https://helsinki.fi
    activate server
    server-->>browser: HTTP status code 302 (Redirect to /exampleapp/notes)
    deactivate server
```
