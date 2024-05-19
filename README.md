# UIR Library Management System (UIRLibMan)

### Description:

UIRLibMan is a robust and user-friendly library management system developed using Python and the Django framework, with SQLite as the database backend. Tailored specifically for educational purposes at the Université Internationale de Rabat (UIR), UIRLibMan facilitates efficient management of library resources while providing distinct interfaces for administrators and students.

### Key Features:

- **User-Friendly Interface**: UIRLibMan offers intuitive interfaces for both administrators and students, ensuring ease of navigation and efficient access to relevant functionalities.

#### Admin Interface:
- **Book Management**: Admins can add new books to the library database, view available books, and manage book details such as title, author, and availability status.
- **Issue and Return**: Admins have the authority to issue books to students and mark them as returned upon completion. They can also track the history of issued books.
- **Student Management**: Admins can view and manage student records, including usernames and issued books.

#### Student Interface:
- **Personal Dashboard**: Students can access their personal dashboard, which displays the books currently issued to them along with the due date for return.
- **Issued Books**: Students can view details of the books they have borrowed, including title, author, and issue date.
- **Return Reminders**: UIRLibMan automatically notifies students about upcoming due dates to facilitate timely returns.

- **Secure Authentication**: UIRLibMan ensures secure authentication mechanisms to safeguard user accounts and sensitive information. Passwords are encrypted to maintain data integrity and confidentiality.
- **Role-Based Access Control**: UIRLibMan implements role-based access control, allowing administrators exclusive rights to manage system functionalities such as book management and user administration, while restricting students to view their own borrowing details.
- **Data Persistence with SQLite**: UIRLibMan utilizes SQLite as the backend database management system, providing lightweight and efficient data storage for managing books, user accounts, and transaction records.
- **Scalability and Extensibility**: UIRLibMan is designed with scalability and extensibility in mind, enabling easy integration of additional features and enhancements as per project requirements and future expansion.
- **Error Handling and Validation**: UIRLibMan incorporates robust error handling and data validation mechanisms to ensure data integrity and system stability, minimizing the risk of erroneous inputs and unexpected behaviors.

UIRLibMan is an ideal solution for educational institutions seeking a comprehensive and customizable library management system for their school projects. With its user-centric design and powerful features, UIRLibMan empowers administrators and students alike to efficiently manage library resources and streamline borrowing processes.

### Running the Program

To run UIRLibMan, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/UIRLibMan.git
   cd UIRLibMan
   ```

2. **Set Up the Virtual Environment:**
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Apply Migrations:**
   ```bash
   python manage.py migrate
   ```

5. **Create a Superuser:**
   ```bash
   python manage.py createsuperuser
   ```

6. **Run the Development Server:**
   ```bash
   python manage.py runserver
   ```

7. **Access the Application:**
   - Open your web browser and go to `http://127.0.0.1:8000/`.
   - Log in using the superuser credentials you created.

### Contribution

This project was developed as a university project guided by Mme Bassma Guermah at Université Internationale de Rabat (UIR).
