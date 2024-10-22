# Job Portal

Job Portal is a MERN Stack-based web app that helps streamline the flow of the job application process. It allows users to select their roles (applicant/recruiter), and create an account. In this web app, login sessions are persistent and REST APIs are securely protected by JWT token verification. After logging in, a recruiter can create/delete/update jobs, shortlist/accept/reject applications, view resumes, and edit profiles. And, an applicant can view jobs, perform fuzzy search with various filters, apply for employment with an SOP, view applications, upload a profile picture, upload a resume, and edit a profile. Hence, it is an all-in-one solution for a job application system.


The directory structure of the web app is as follows:

```
- backend/
    - public/
        - profile/
        - resume/
- frontend/
- README.md
```

## Instructions for initializing web app:

- Install Node JS, MongoDB in the machine.
- Start MongoDB server: `sudo service mongod start`
- Move inside backend directory: `cd backend`
- Install dependencies in backend directory: `npm install`
- Start express server: `npm start`
- Backend server will start on port 4444.
- Now go inside frontend directory: `cd ..\frontend`
- Install dependencies in frontend directory: `npm install`
- Start web app's frontend server: `npm start`
- Frontend server will start on port 3000.
- Now open `http://localhost:3000/` and proceed creating jobs and applications by signing up in required categories.

![Picture1](https://github.com/user-attachments/assets/6a7f5fbd-e063-4cc7-a8df-f39e4cfe639d)
![Picture2](https://github.com/user-attachments/assets/71e407b7-38a6-496f-881a-1767644109fa)
![Picture3](https://github.com/user-attachments/assets/4c83c540-7a0f-4a06-a5be-fc93fe2666be)
![Picture4](https://github.com/user-attachments/assets/536be1e2-d4db-45d0-ad8d-3d59dc837026)
![Picture5](https://github.com/user-attachments/assets/74871dcc-ec63-43de-a669-6d8109844a73)
![Picture6](https://github.com/user-attachments/assets/646089dd-10aa-43ff-9582-bc85dde95eac)
![Picture7](https://github.com/user-attachments/assets/80c661c7-b8a7-478d-8708-5c01f3f295be)
![Picture8](https://github.com/user-attachments/assets/06a99297-ee51-407c-993f-0bad3952c9b7)
![Picture9](https://github.com/user-attachments/assets/06a44156-a992-46ca-8ff4-ec291112d582)
![Picture10](https://github.com/user-attachments/assets/c9c69c66-54a0-420e-b8fd-134d030cd9ad)




## Dependencies:

- Frontend
  - @material-ui/core
  - @material-ui/icons
  - @material-ui/lab
  - axios
  - material-ui-chip-input
  - react-phone-input-2
- Backend
  - bcrypt
  - body-parser
  - connect-flash
  - connect-mongo
  - cors
  - crypto
  - express
  - express-session
  - jsonwebtoken
  - mongoose
  - mongoose-type-email
  - multer
  - passport
  - passport-jwt
  - passport-local
  - uuid

