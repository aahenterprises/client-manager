# Client Manager

A cloud-based client management (CRM) web app built by **AAH Enterprises**. Log in securely, then add, edit, search and track your clients from any device.

## Features

- Secure login with Firebase Authentication (email and password)
- Add, edit and delete clients
- Track each client's project, status (Lead, Active, Completed) and amount
- Live KPI cards: total clients, active clients, leads and total value
- Search by name, project, phone or email, and filter by status
- Data stored in the cloud (Firebase Firestore), so it works on any device
- Each user can see only their own clients
- Loading logo animation and responsive gradient design

## Built with

- HTML5
- CSS3 (gradients, grid, animations)
- JavaScript (ES modules)
- Firebase Authentication
- Firebase Firestore (cloud database)

## How to run

1. Download or clone this repository.
2. Open `index.html` in a browser.
3. Log in with an account created in your own Firebase project.

To use your own database, create a Firebase project, enable Email/Password sign-in and Firestore, then replace the `firebaseConfig` values inside `index.html`.

## Security note

The Firebase config in a web app is public by design. Data is protected by Firestore security rules, which allow each logged-in user to read and write only their own records.

## Author

**Muhammad Awais Raza**, Founder & CEO, AAH Enterprises
Email: contact.aahenterprises@gmail.com
GitHub: [github.com/aahenterprises](https://github.com/aahenterprises)

&copy; 2026 AAH Enterprises<img width="1355" height="606" alt="Screenshot 2026-10-16 010212" src="https://github.com/user-attachments/assets/6ecfea75-4fb4-41c9-a7de-0008939a810e" />
<img width="1255" height="605" alt="Screenshot 2026-10-16 010307" src="https://github.com/user-attachments/assets/c2e2e218-ea39-4a15-a134-ae39b062f775" />
<img width="1234" height="575" alt="Screenshot 2026-10-16 010357" src="https://github.com/user-attachments/assets/57675af9-99e5-439f-b9c6-b21bb5638ebd" />
<img width="1234" height="575" alt="Screenshot 2026-10-16 010357" src="https://github.com/user-attachments/assets/fe24ea38-0596-47fc-89f1-732962f7859f" />
<img width="1127" height="481" alt="Screenshot 2026-10-16 010525" src="https://github.com/user-attachments/assets/db6ba155-7f27-461c-9610-3f7c9cf338bf" />
<img width="969" height="313" alt="Screenshot 2026-10-16 010618" src="https://github.com/user-attachments/assets/5b4bab1d-0581-4745-b840-d66e3f20a84e" />
