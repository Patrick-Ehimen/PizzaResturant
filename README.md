# Project Overview

## Fast React Pizza Co.

This project is a web application for a pizza restaurant named "Fast React Pizza Co." It allows users to browse the menu, add pizzas to their cart, and place orders with optional priority. The application is built using React and Redux Toolkit, and it integrates with a backend API for fetching menu items and managing orders.

### Key Features

- **Menu Browsing**: Users can view a list of available pizzas and their details.
- **Cart Management**: Users can add pizzas to their cart, adjust quantities, or remove items.
- **Order Placement**: Users can create orders, optionally adding priority to their orders for faster delivery.
- **User Interaction**: New users can enter their names, and the application will remember them.
- **Responsive Design**: The application is responsive and works well on both desktop and mobile devices.

### Technologies Used

- **React**: For building the user interface.
- **Redux Toolkit**: For state management across the app.
- **Tailwind CSS**: For styling the application.
- **React Router**: For navigation within the application.

### Setup and Running

1. Clone the repository.
2. Install dependencies using `npm install`.
3. Start the development server using `npm start`.

### Code Structure

- `src/`: Contains all the source code for the application.
  - `features/`: Feature-specific components and Redux slices.
  - `ui/`: Reusable UI components like buttons and loaders.
  - `services/`: Services for API calls.
  - `utils/`: Utility functions for formatting and calculations.
  - `store.js`: Redux store configuration.
  - `App.jsx`: Main component that sets up routing and layout.
- `public/`: Public assets like images and the index.html file.

### CSS Styling

The application uses Tailwind CSS for styling, configured in `src/index.css`. Components use utility classes from Tailwind to maintain a consistent look and feel.

### Redux State Management

State management is handled by Redux Toolkit. The application has slices for user data, cart data, and order data, allowing for efficient and organized state updates.

### API Integration

The application communicates with a backend API for data fetching and updates. API calls are made in the `services/` directory, using the native `fetch` API.

### Future Enhancements

- Implement user authentication.
- Add more interactive elements to the menu items.
- Improve error handling and user feedback.

This README provides a high-level overview of the Fast React Pizza Co. web application, its features, and technical details. For more specific information, refer to the inline documentation within the codebase.
