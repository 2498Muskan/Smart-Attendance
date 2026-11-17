# College Smart Attendance — React + Node + MySQL

1. Import `database/schema.sql` using phpMyAdmin.
2. In `server`, run `npm install`, copy `.env.example` to `.env`, edit MySQL settings, then run `npm run seed` and `npm run dev`.
3. In `client`, run `npm install` and `npm run dev`.
4. Open http://localhost:5173.

Demo: admin@example.com / admin123 ; teacher@example.com / teacher123.
CSV headers: `Roll Number,Student Name`.
Teachers can be assigned multiple sections. In attendance, enter only present IDs (e.g. X1, X2); everyone else is marked absent. Full roll numbers are accepted too.
