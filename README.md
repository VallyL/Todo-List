# Interactive Todo List with User ID Search and Styling

# Description: 
  This project implements a dynamic Todo List application that fetches data from the DummyJSON API and displays it in an interactive list. Users can search for todos 
  by their associated user ID, and the UI updates dynamically to reflect the search results.

# Key Features:
  - API Integration: Fetches todo data from the DummyJSON API using fetch.
  - Dynamic Rendering: Renders fetched todos into an ordered list (<ul>) with user ID, todo description, and completion status.
  - User ID Search: Allows users to search for todos by their user ID using an input field.
  - Design of search results: highlights the searched tasks, moving them to the top of the list and applying subtle animation.
  - Visual Clarity: Uses CSS classes to visually separate completed and pending tasks, improving readability.

# How it works:
  - Fetch Todos: The getAllTodos function fetches todo data from the API using fetch.
  - Render Todos: The renderTodos function dynamically creates list items for each todo and appends them to the todosContainer element.
  - Search Functionality: The searchTodosById function filters the displayed todos based on the user ID entered in the search input field.
  - Interactive Search: An input event listener is attached to the search input to trigger the search functionality as the user types.

# Technologies:
  - HTML
  - CSS
  - JavaScript (async/await, DOM manipulation, event listeners)

# Contributions are welcome! Feel free to fork the repository and suggest improvements or new features.
