# LmsBasicFrontend

The Library Management System with a basic frontend that only uses <ins>core</ins> html, css, and js.

**Project Run Notes:**

- Open index.html in a web browser.

- Core Javascript doesn't allow direct access to a local filesystem. To make the admin validation and book CRUD work properly, you need to add/copy the below key-value entries into your web browser's localStorage (ideally before opening the index).

  - key: users \
    value: everything in users.json

  - key: myBooks \
     value: everything in testData.json
    "# library-management"
