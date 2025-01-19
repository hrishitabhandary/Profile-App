**Profile Web Application**

This web application allows users and administrators to manage and view profiles. Users can browse through profiles, read detailed information, and use a map integration to view locations. The search and filter functionalities make it easy to find profiles based on various criteria, including name, location, and description.

For administrators, the application offers features to view, delete, and add profiles. The admin section currently lacks the ability to add new profiles (due to a technical issue with the "Add Profile" button) and does not yet support editing profiles. However, the application is designed with a user-friendly interface using modern technologies like React.js, Bootstrap, and OpenStreetMap for map integration.

### 1. Clone the repository
To run the project in development mode:
```bash
npm start
```

### 2. Install dependencies
Navigate to the project directory:
```bash
cd <project_directory>
```

Then, install the required dependencies:
```bash
npm install
```

### 3. Start the project
To run the project in development mode:
```bash
npm start
```

The application will start running on `http://localhost:3000`.

## Login Instructions

### Admin Login:
- **Email**: admin@example.com
- **Password**: admin@123

### User Login:
1. **User 1**:
   - **Email**: user1@example.com
   - **Password**: user@123
2. **User 2**:
   - **Email**: user2@example.com
   - **Password**: user@456

## Features

### User Section:
1. **Displays all profiles**: A list of user profiles is shown.
2. **Read More Button**: Clicking the "Read More" button on a profile will display detailed information, including the address displayed using OpenStreetMap integration.
3. **Search/Filter Functionality**: Search or filter profiles based on criteria such as name, location, and description.

### Admin Section:
1. **Displays all profiles**: The admin can view a list of all user profiles.
2. **Delete Profile**: Admin has the option to delete any profile from the system.
3. **Add Profile**: Admin can add new profiles, but **the "Add Profile" button is currently not working**.
4. **Edit Profile**: Admin can view profile details, but **the feature to edit profiles has not been added yet**.

## Technologies Used:
- HTML
- CSS
- Bootstrap
- Tailwind CSS
- React.js
- OpenStreetMap (for map integration)
