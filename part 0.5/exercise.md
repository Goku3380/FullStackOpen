``` mermaid
sequenceDiagram
    User->>+Server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/notes
    Server-->>+User: html code
    User->>+Server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/notes with Content/JSON header
    Server-->>-User: json file 