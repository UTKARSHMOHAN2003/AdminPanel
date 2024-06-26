# Project Admin Panel

This project is a simple admin panel built using React Redux Toolkit (RTK) that allows administrators to manage users. The admin can perform various operations such as adding new users using the Chance API, deleting a single user, or deleting all users at once.

## Features

- **Add New User:** Administrators can add a new user by generating random user data using the Chance API and storing it in the system.
- **Delete Single User:** Administrators have the capability to delete a single user from the system.
- **Delete All Users:** Administrators can delete all users from the system with a single action.

## Technologies Used

- React: A JavaScript library for building user interfaces.
- Redux Toolkit (RTK): An opinionated, batteries-included toolset for efficient Redux development.
- Chance API: A random data generator API used for generating user data.
- Axios: A promise-based HTTP client for making API requests.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/admin-panel.git
    ```

2. Navigate to the project directory:

    ```bash
    cd admin-panel
    ```

3. Install dependencies:

    ```bash
    npm install
    ```
     ```bash
    npm install @reduxjs/toolkit
    ```
      ```bash
   npm install react-redux
    ```
    ```bash
   npm install chance
    ```

4. Start the development server:

    ```bash
    npm start
    ```

5. Open your browser and go to [http://localhost:3000](http://localhost:3000) to view the admin panel.

## Usage

1. Upon launching the admin panel, you will be presented with a dashboard displaying existing users (if any).
2. To add a new user, click on the "Add User" button. This will generate random user data using the Chance API and add it to the system.
3. To delete a single user, click on the "Delete" button next to the user you wish to remove.
4. To delete all users at once, click on the "Delete All Users" button.

## Contributing

Contributions are welcome! If you find any bugs or want to improve the project, feel free to open an issue or submit a pull request.


**Note:** This project is for demonstration purposes and may not be suitable for production environments. Use it at your own risk.
