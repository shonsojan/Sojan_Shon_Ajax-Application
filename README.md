# Ajax-Application

A dynamic webpage showcasing earbuds' features using hotspots, Fetch API, and modern web technologies.

---

## ✨ Features

- **Dynamic Content**: Fetches data about the earbuds using the Fetch API on page load.
- **HTML Template Element**: Utilized to display material dynamically.
- **Loading Indicator**: Shows a loading icon while fetching data.
- **Interactive Hotspots**: Updates the view with API data as users interact with hotspots.

---

## 🛠️ Technologies Used

- **HTML**: Structure of the page, including the `<template>` element.
- **CSS/SASS**: For styling and preprocessed CSS.
- **JavaScript**: Includes ES6 features for interactivity.
- **Fetch API**: To retrieve data dynamically.
- **AJAX**: For handling asynchronous data requests.

---

## ⚙️ Setup Instructions

1. Clone the repository.
2. Open the project folder in your preferred code editor.
3. Update the `API_URL` variable in the JavaScript file to the provided API endpoint.
4. Use a local server (e.g., Live Server for VS Code) to test the project, as Fetch API may require an HTTP environment.
5. Open the `index.html` file in your browser to view the page.

---

## 🔍 Functionality Breakdown

1. **AJAX Request Stages**:

   - A loading icon appears during the fetch request.
   - Data is retrieved from the API and stored in the application state.
   - On success, the view is updated dynamically.
   - On failure, a message is displayed to inform the user.

2. **HTML Template Element**:

   - Templates are used to render the API data, ensuring reusability and clean code.

3. **Hotspot Interaction**:
   - Clicking on hotspots triggers updates to display corresponding details about the earbuds.

---

## 🤝 Contributions

This is an individual project. For questions or clarifications, feel free to reach out.

---

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
