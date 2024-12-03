# Alumni-Connect-Bridging-Future

## Project Description
**Alumni Connect** is a platform designed to facilitate interaction between alumni and students, providing features like job postings, alumni search, and user role-based access control (RBAC). The platform allows users to access functionalities based on their roles, such as Admin, Alumni, and Student.

## Position: Frontend Developer

### Responsibilities:
- Developed the **RBAC UI** to ensure appropriate access levels for Admins, Alumni, and Students.
- Implemented dynamic components for managing user roles and job posting approvals.
- Ensured **responsive design** and **cross-browser compatibility** using **TailwindCSS**.
- Integrated **API calls** with backend endpoints for seamless role-based functionalities.

---

## Key Features of the RBAC UI

### 1. **Role-Based Views:**

- **Admin**:
  - Admin is the superuser who manages the entire platform. Only admins can create and manage users (students) who access the platform with their college-provided email and password.
  - **Job Postings**: Admin and Alumni can post jobs. However, only the job poster (Admin or Alumni) can delete a job post. Admin has the ability to **activate** and **deactivate** job posts, which determines visibility to students.

- **Alumni**:
  - Post and manage job opportunities.
  - View and interact with student profiles.

- **Students**:
  - Access job postings.
  - Search alumni profiles.

### 2. **Dynamic Role Assignment**:
- Admin can change the role of any user and update their details.

### 3. **Secure Authentication**:
- Authentication is managed via **JWT tokens**.
- The database used is **MongoDB Atlas** for storing user data.

---

## Accessing the Project

- **Live Deployment**: [Alumni Connect Platform](https://alumni-client-side-by5mbdexr-shivs-projects-0bdf001e.vercel.app)

### Access Login Details for Roles:

- **Admin**:
- There is only a single admin: 
  Email: `admin@gmail.com`  
  Password: `Pass@1234`  

- **Alumni**:  
  Email: `nav@gmail.com`  
  Password: `Pass@1234`
  /* in any case not working please create a new user via admin panel.

- **Student**:  
  Email: `ravi@gmail.com`  
  Password: `Pass@1234`
  /* in any case not working please create a new user via admin panel.

---

## Testing the RBAC UI

### **Admin Panel**:
1. Log in as an Admin.
2. Test **role management** features.
3. Approve or delete a job posting.
4. Create users and update their role and details.
5. Test login functionality with the created admin users.

### **Alumni Panel**:
1. Post a new job opportunity.
2. Edit or delete existing job postings.
3. Alumni posted jobs will be inactive which can be active by admin.
   

### **Student Panel**:
1. Search for alumni profiles.
2. View & Search Activejob postings.

### **Expected Behavior**:
- Each role should only have access to its permitted features.
  - Admins can manage users and job posts.
  - Alumni can post and manage jobs.
  - Students can only view job postings and search for alumni profiles.

## Technologies Used:
- **Frontend**: React, TailwindCSS
- **Backend**: MongoDB Atlas (for storing data), JWT Authentication
- **Deployment**: Vercel (for live deployment)

---

## Contributing

Feel free to fork this project and contribute to improvements. If you encounter any bugs or have suggestions, please open an issue or submit a pull request.

---
### **Build Date: April 2024**
