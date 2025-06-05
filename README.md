#  Fetch and Display Data from a Public API

This project demonstrates how to use the JavaScript `Fetch API` to retrieve user data from a public API and display it in a styled HTML table. It includes error handling, a responsive layout, and a reload button to refetch data.

---

##  Objective

Use the Fetch API to:
- Request user data from a public API.
- Display user name, email, and address.
- Handle errors gracefully.
- Style the content using CSS.
- Make it responsive and interactive.

---

## 🛠️ Tools & Technologies Used

- HTML5  
- CSS3  
- JavaScript (ES6)  
- Fetch API  
- [JSONPlaceholder API](https://jsonplaceholder.typicode.com/users)

---
##  Features

-  Fetches user data from a public API
-  Displays data in a well-styled table
-  "Reload" button to refetch data on demand
-  Error message shown on failed fetch
-  Responsive table design with horizontal scroll on smaller screens
-  Disabled button state with no transitions while loading
---
## Error Handling

- If the API fetch fails (e.g., no internet), a styled error message Error fetching users! is displayed.
- The table is hidden if there's no valid data.

