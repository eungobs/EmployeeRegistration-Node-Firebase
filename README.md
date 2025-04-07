![Untitled (9)](https://github.com/user-attachments/assets/263d67f2-edf4-4bce-9ded-83693d178d25)

Here's the revised README file, incorporating the provided repository URL:


# Teekga ELECTRICAL Company Registration App

Welcome to the Teekga ELECTRICAL Company Registration App! This application is designed to help manage employee records efficiently. It allows an admin to securely log in and perform various operations involving employee data, such as adding, updating, and deleting records. The app also provides insights into the status of employees, including those who are active, deactivated, or have transferred to other branches.

You can try out the application here: [Demo Link](https://employee-registration-node-firebase-ywyn.vercel.app).

## Key Features

- **Admin Access Only**: This app is for admins only! Only authorized users can log in to manage employee records. Admin login details are as follows:
  - **Username**: elizabeth.ndzukule@gmail.com
  - **Password**: 000000

- **View Employee Status**: You can see employees categorized by their work status, including active employees, those who are not currently active (deactivated), and those who have moved (transferred) to other branches.

- **Responsive Design**: The application works beautifully on any device, whether it’s a desktop computer or a mobile phone, ensuring a great user experience wherever you are.

- **Built-in Security**: The app focuses on keeping employee data secure, so you can manage your information safely.

## Technologies Used

The app is built using the following technologies:

- **React.js**: This is a tool that helps build the user interface (what you see on the screen) and manage how it behaves.
- **Node.js**: This is used for the backend (the part that runs on the server and handles requests) to store and manage all the data.
- **Firebase**: This service is used for user authentication (making sure only authorized users can log in) and storing employee data.
- **JavaScript**: This is the programming language that runs the app's core functionality.
- **CSS**: This styling language makes the app look modern and responsive.

## How to Install and Set Up the Application

To get this app up and running on your computer, follow these simple steps:

1. **Clone the Repository**: This means making a copy of the app’s files on your computer.
   - Open your terminal (like Command Prompt or PowerShell) and type:

     git clone https://github.com/eungobs/EmployeeRegistration-Node-Firebase.git
     cd EmployeeRegistration-Node-Firebase
 

2. **Install Frontend Dependencies**: This step ensures that all the tools the app needs are ready to go. Type:

   npm install
 

3. **Set Up the Backend**: 
   - Navigate to the backend directory (if there is one; adjust accordingly) and run:
   
     cd backend
     npm install
     npm start
  

4. **Open the App**: After the backend is running, open your web browser and go to [http://localhost:3000](http://localhost:3000) to see the app.

## How to Use the App

### Landing Page
- When you first arrive at the app, click the "Admin" button to register as a new admin. Once registered, use the admin credentials provided above to log in.

### Active Employees Page
- After logging in, you will find yourself on the **Active Employees** page. Here, you can see all current employees and manage their records. The page includes:

  - **Action Buttons**:
    - **Add**: This button lets you open a form to add a new employee.
    - **Edit**: You can edit the details of an employee. This button will be found within each employee's card.
    - **Delete**: You can delete an employee from the system. Once you confirm, they will be removed.
    - **Personnel**: Click this to view employees who have resigned, transferred, or been promoted.
    - **Logout**: This button lets you log out securely when you're done.

- **Employee Cards**: Each card displays information about an individual employee, including their details and options to edit or delete.

## Author

This project was completed by **Elizabeth Eunice Ndzukule** in just 5 days, showcasing rapid development abilities. I developed the app using Visual Studio Code, and the initial designs were created with Figma. You can find screenshots of the app in the public folder of the project.

## Additional Information

The Teekga ELECTRICAL Company Registration App is designed with an emphasis on security and a user-friendly experience. It allows the company’s admin to manage employee data efficiently and safely from anywhere, using any device.

If you have any questions or need further assistance, feel free to reach out! Enjoy using the app!



This README now includes your provided repository URL and maintains a user-friendly language for individuals who are not familiar with coding.
