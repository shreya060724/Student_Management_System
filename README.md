# **Student Management System**  

A **Django-based Student Management System** with **SQL Workbench**, designed to manage student records efficiently. It supports **Admins, Students, and Faculty** with role-based authentication and key academic management features.  

## **Features**  
✅ **Secure Authentication** – Role-based login for Admins, Students, and Faculty.  
✅ **Attendance Management** – Track and manage student attendance.  
✅ **Feedback System** – Students can submit feedback for faculty review.  
✅ **Leave Application** – Students can apply for leave with an approval workflow.  
✅ **User-Friendly Interface** – Built using Bootstrap for a responsive UI.  

## **Tech Stack**  
- **Backend:** Django  
- **Database:** SQL Workbench  
- **Frontend:** HTML, Bootstrap, JavaScript  

## **Installation**  

1. **Clone the repository**  
   ```bash
   git clone https://github.com/yourusername/student-management-system.git
   cd student-management-system
   ```  

2. **Create a virtual environment**  
   ```bash
   python -m venv venv  
   source venv/bin/activate  # For macOS/Linux  
   venv\Scripts\activate  # For Windows  
   ```  

3. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```  

4. **Run migrations**  
   ```bash
   python manage.py migrate
   ```  

5. **Start the development server**  
   ```bash
   python manage.py runserver
   ```  

## **Usage**  
- Admin can manage students, faculty, and records.  
- Students can mark attendance, apply for leave, and give feedback.  
- Faculty can track student progress and review feedback.  

## **Contributing**  
Contributions are welcome! Feel free to fork the repo, create a new branch, and submit a pull request.  

## **License**  
This project is **open-source** under the **MIT License**.  

🚀 **Star this repo if you find it useful!** 😊  

