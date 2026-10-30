sequenceDiagram
  participant browser
  participant server

  browser->>server: GET https://studies.cs.helsinki.fi/exampleapp/spa
  activate server
  server-->>browser:
  deactivate server

  browser->>server: GET https://studies.cs.helsinki.fi/exampleapp/
  activate server
  server-->>browser:
  deactivate server

  browser->>server: GET https://studies.cs.helsinki.fi/exampleapp/
  activate server
  server-->>browser:
  deactivate server

  browser->>server: GET https://studies.cs.helsinki.fi/exampleapp/
  activate server
  server-->>browser:
  deactivate server
