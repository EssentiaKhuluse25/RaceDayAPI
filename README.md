# RaceDay - Part 2 RESTful API

### Setup Instructions
1. Open the solution in Visual Studio 2022.
2. Ensure SQL Server is running and the connection string in `appsettings.json` is correct.
3. Open Package Manager Console and run `Update-Database` to create the database.
4. Press `F5` to run the API. Swagger UI will open in your browser.

### Roles
*   **Organiser:** Can create, update, and delete events.
*   **Participant:** Can view events and enrol in them.
*   *Note: Passwords are securely hashed using BCrypt.*

### CI/CD Pipeline
*(CI/CD workflow builds and tests the API on every push).*
[DRAG AND DROP YOUR GREEN CHECKMARK SCREENSHOT HERE]

### Unit Tests
*(Tests validate user registration and role-based access).*
[<img width="1365" height="401" alt="Screenshot 2026-10-19 172355" src="https://github.com/user-attachments/assets/6cdd8d9e-8967-4ce2-94b3-791fd3610642" />
]

