CAMPUSCONNECT FULL FRONTEND PROTOTYPE

Included: student sign-in/profile, dashboard, weekly timetable, attendance tracker, subject-wise attendance, notice board, labs/workshops/holidays, faculty status, admin tools to add students, edit schedule, publish notices and events, update faculty availability, export local backup.

DEMO ACCOUNTS
Student: student@campusconnect.demo / student123
Admin: admin@campusconnect.demo / admin123

GITHUB PAGES UPDATE (Android)
1. Extract this ZIP on your phone.
2. Open your Campus-connect GitHub repository.
3. Upload index.html to repository root and confirm replacement of the old index.html.
4. Commit changes. Wait for GitHub Pages to redeploy, then refresh the site.

IMPORTANT LIMITATION
This is a functional FRONTEND prototype. It stores demo data in the current browser's localStorage. Student accounts, attendance, timetable, notices and faculty updates do NOT sync between different phones or users and demo credentials are not secure authentication. Faculty availability is manually entered, not live. Do not use for real student records.

To turn this into a real online system, connect a backend such as Firebase Authentication + Firestore (or an institution-approved backend), define role-based security rules, create college-admin accounts, migrate timetable/student data, and test privacy/security. That requires Firebase project configuration and college approval; this ZIP cannot create those accounts or a live backend by itself.
