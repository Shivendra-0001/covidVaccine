<h1>DevRev assignment:</h1>
<h2>Covid vaccination slot booking project</h2>


## Getting Started

To run this project on local pc:

```bash
 Clone the repo.
 npm install.
 npx prisma generate.
 npm run dev.
```
<pre>
Features:
*User Registration and Login:

*Users can create an account by signing up with their details.
 -Existing users can log in to access the application.
 -User Profile Management:

*Users can view and update their profile information.
 -Profile data validations are applied during registration and updates.
 -Vaccination Centre Search:

*Users can search for vaccination centres based on location or other criteria.
 -The application provides information about the centres, including working hours.
 -Vaccination Slot Booking:

*Users can apply for a vaccination slot at their preferred centre.
 -Only 10 candidates are allowed per day, so the application should enforce this limit.
 -Users can select an available slot and book it for themselves.

 
*User Logout:
 -Users can securely log out of their accounts.

 
*Admin Login:

 -Admins have separate credentials to access the application's admin features.
 -Vaccination Centre Management (Admin):

 -Admins can log in to the application with their credentials.
 -Admins can add new vaccination centres to the system.
 -Admins can remove existing vaccination centres from the system.
 -Dosage Details (Admin):

 -Admins can view dosage details aggregated by vaccination centres.
 -This feature provides information on the number of dosages administered at each centre.
 </pre>


