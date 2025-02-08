# Hospital Management System with JSP and Java

This is a **Hospital Management System** developed using **Java** and **JSP (Java Server Pages)**, designed to manage appointments, doctor-patient interactions, and admin functionalities. The system supports **three user roles**: **Admin**, **Doctor**, and **User**, each with its own personalized dashboard and access rights.

### Key Features:

#### **For Users**:
- **Registration**: New users can register from the homepage.
- **Appointment Management**: Users can **login**, view available doctors, and **make appointments** based on their preferred doctor and specialty. Users can also view and manage their appointments.
- **Navbar with User Info**: The navbar shows the logged-in user's name and provides a logout option for easy session management.

#### **For Doctors**:
- **Doctor Login & Dashboard**: Doctors can **login** to access their dashboard. The dashboard shows the total number of appointments and a list of patients along with their current status (e.g., Pending, Completed).
- **Patient Management**: Doctors can view patient details and update the status (e.g., mark a check-up as completed or leave a comment if it's pending).
- **Profile Options**: Doctors have a dropdown in the navbar to access their profile settings, edit profile information, or logout.

#### **For Admin**:
- **Admin Login & Dashboard**: The admin has access to a home page that displays total numbers of doctors, appointments, specialists, and users in card format.
- **Manage Doctors & Specialties**: Admin can add new doctors, edit their details, or delete them. They can also manage doctor specialties by adding new specialties.
- **Patient Information**: Admin has access to patient records and can view appointment statuses.
- **Doctor Management**: Admin can view doctor details, edit profiles, and manage doctor statuses.
  
### Navbar Options (Role-Specific):
- **For User**: Displays the user's name, with options to make an appointment or view current appointments.
- **For Doctor**: Includes a dropdown with the doctor’s name, options to edit the profile, and logout.
- **For Admin**: Includes options to manage doctors, view doctors, manage patients, and logout.

### Technologies Used:
- **Backend**: Java, JSP, Servlets
- **Frontend**: HTML, CSS, Bootstrap (for responsive design)
- **Database**: MySQL (or any relational database)
- **Server**: Apache Tomcat (for running JSP/Servlets)

### Key Functionalities:
- **User Role Management**: Three user roles (Admin, Doctor, User) with distinct dashboards and access rights.
- **Appointment Management**: Users can book, view, and manage their appointments with doctors.
- **Doctor Dashboard**: Doctors can view their appointments, update patient statuses, and provide comments.
- **Admin Dashboard**: Admin can manage doctors, specialties, and patients, as well as track appointments.
- **Dynamic Navbar**: Navbar changes based on user roles, showing role-specific options like profile settings and logout.

### Future Enhancements:
- **Appointment Notifications**: Add email or SMS notifications to remind users of upcoming appointments.
- **Medical Records**: Implement a feature for doctors to maintain patient medical records.
- **Advanced Doctor Search**: Implement search filters for users to find doctors based on specialties, ratings, or location.
- **Doctor Ratings**: Allow patients to rate doctors after an appointment.
- **Appointment Scheduling Optimization**: Add functionality to optimize appointment scheduling based on doctor availability.

Feel free to fork this repository, contribute, and share your ideas for further improvements!
