# Mock_Admin_Panel_Data
This repository provides mock data that simulates fetching from an API for the Admin Panel mockups.

Example (Using Fetch API):
```js
const res = await fetch(
    `https://cdn.jsdelivr.net/gh/buildingu/Mock_Admin_Panel_Data@main/api/v1/blogs/blogs.json`,
    { method: "GET" }
  ),
  data = await res.json();

if (!res.ok)
  // Handle error response.

// Handle success response.
```
