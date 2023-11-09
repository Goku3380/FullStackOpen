```mermaid
graph TD
    A[Type a note in the input] -->|Press save button| B(POST https://studies.cs.helsinki.fi/exampleapp/newnote)
    B --> C(Server Response 302)
    C -->|Redirect to note page| D[I can see my note :D]
