# CHIPin
The following instructions will help you get CHIPin installed and working for development.
##
### 1. Ensure you have the following installed:
  - Docker Desktop
  - Node.js
  - Java JDK 21
  - Expo Go version 57.0.17

### 2. Clone the repo
### 3. Create a new `.env` file in the root folder
### 4. Copy the contents of `.env.example` into `.env`
  - Fill out `DB_NAME`, `DB_USER`, and `DB_PASSWORD`

### 5. Navigate to the mobile folder
### 6. Create a new .env file in the mobile folder
7. Copy the contents of `.env.example` into `.env`
  - use ipconfig to find your ipv4 address
  - replace "your device ip" with your ipv4 address
### 8. While still in the mobile folder, right click and open select "open terminal"
### 9. Run `npm install` to install the dependencies needed for mobile development
### 10. Run `cd..` to get back to the root directory
### 11. Run `docker compose up --build`
  - this brings up Spring Boot, PostgreSQL, and Adminer
### 12. Open a new terminal in the mobile folder
### 13. Run `npx expo start`
### 14. Scan the QR code to ensure your app is set up as expected.
##
Now that you are set up, you can begin developing the project using AGILE framework by utilizing Jira to create branches based off specific SCRUM tasks

Our tech stack is as follows:
- FRONTEND: React Native via Expo Go, stylized with NativeWind (Tailwind CSS for React Native)
- BACKEND: Spring Boot, Spring Security, Spring Data JPA
- DATABASE: PostgreSQL 16 via Adminer

With our BACKEND and DATABASE containerized via Docker Compose

   
