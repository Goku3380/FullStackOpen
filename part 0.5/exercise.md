```mermaid
   graph TD
    A[Type a note in the input] -->|Press save button| B(JS Code execute to send HTTP POST 
    request to https://studies.cs.helsinki.fi/exampleapp/notes to add my note)
    B --> C(Server Response 201)
    C -->|Js code make a change in the notes list, adding my note| D[I can see my note :D]
