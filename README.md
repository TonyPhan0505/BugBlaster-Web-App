# BugBlaster
This is a web app for software development teams to track the progress of fixing bugs in their software and continuously get client feedback throughout the development process.

# Live link:
https://bugblaster.netlify.app

# Features:
- Secure authentication.
- Client can find the link to their continuously deployed app in the same place as where they can raise issues to the developers.
- An email is sent to the development team for each issue reported. This makes it much easier for the developers to manage bugs for different clients at once, because then a developer can query for bugs specific to a project in their email inbox.
- Simple, intuitive and effective user interface for mobile and desktop devices.
- Seamless user experience.

# Demo:
https://www.youtube.com/watch?v=1NZkYH_4QL0

# Screenshots:
### Login and Sign up:
<img width="1920" height="1000" alt="loginsignup1" src="https://github.com/user-attachments/assets/863de05a-9dc0-4e45-9931-d1386501e3e6" />
<img width="1920" height="998" alt="loginsignup2" src="https://github.com/user-attachments/assets/bbbbf1b4-953b-4dde-934c-6eb40231bae3" />

### Create a new issue:
<img width="1920" height="1000" alt="create" src="https://github.com/user-attachments/assets/0315bdfa-a116-4410-866f-a91da2da5348" />

### See resolved and unresolved issues, and search by ID, title and description:
<img width="1920" height="998" alt="see" src="https://github.com/user-attachments/assets/511585d1-906c-4b8e-b0f2-28ea46015dd5" />

### Edit and delete an issue:
<img width="1920" height="997" alt="editanddelete" src="https://github.com/user-attachments/assets/e2f1dab2-4361-498f-8943-a81db79f4759" />


# Running the web app
1. cd into the "backend" directory.
2. Run the command: npm install
3. Create a .env file in the "backend" directory in which the values for the following fields are specified: MONGO_USER, MONGO_PASSWORD, ADMIN_EMAIL_ADDRESS, ADMIN_LOGIN_SECRET_KEY, LOGIN_SECRET_KEY, EMAIL and EMAIL_PASS.
4. Run the command: npm start
5. cd into the "frontend" folder.
6. Run the command: npm install
7. Run the command: npm start
