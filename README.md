# Introduction
To add Authentication with JWT to an existing Kanban board application.
With a Kanban board application has alreadycreated.
My job was to complete the UI for the login page, add authentication with JWT to the server API, and then deploy the entire application to Render.

# Acceptance Criteria
GIVEN a Kanban board with a secure login page
WHEN I load the login page
THEN I am presented with form inputs for username and password
WHEN I enter my valid username and password
THEN I am authenticated using JSON Web Tokens (JWT) and redirected to the main Kanban board page
WHEN I enter an invalid username or password
THEN I am presented with an error message indicating that the credentials are incorrect
WHEN I successfully log in
THEN a JWT is stored securely in the client's local storage for subsequent authenticated requests
WHEN I log out
THEN the JWT is removed from the client's local storage and I am redirected to the login page
WHEN I try to access the Kanban board page without being authenticated
THEN I am redirected to the login page
WHEN I remain inactive for a defined period
THEN my session expires, the JWT is invalidated, and I am redirected to the login page upon my next action

# Deployment Link:
Link: https://chal14-authentication.onrender.com


# ScreenShots:
![Screenshot 2025-02-25 181039](https://github.com/user-attachments/assets/ef67bb15-75f2-41f6-91d4-6b7cbf32c4c3)
![Screenshot 2025-02-25 180947](https://github.com/user-attachments/assets/11bb5c7d-40ae-420f-8e1e-84fd113f621f)
![Screenshot 2025-02-25 181011](https://github.com/user-attachments/assets/1e85f526-336a-475d-a50d-1fea53de6be7)
![Screenshot 2025-02-25 181025](https://github.com/user-attachments/assets/7763a160-4b8d-48da-b574-ebb097249ae2)
