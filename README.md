# Student Grading & Academic Management System

A full-stack academic management system designed to manage students, courses, grades, attendance, and transcripts in a structured and secure way.

This project is built incrementally from core features to advanced, production-level capabilities and is suitable for:
- Educational institutions
- Academic demonstrations
- Portfolio and capstone projects

---

## 🎯 Project Purpose

The goal of this system is to:
- Digitally manage academic records
- Support role-based access (Admin, Teacher, Student)
- Ensure accurate grading and GPA calculation
- Provide analytics on academic performance
- Maintain auditability and data integrity

This project follows **real-world academic workflows**, not toy examples.

---

## 👥 User Roles

| Role | Description |
|---|---|
| **Admin** | Manages users, courses, enrollments, grading rules |
| **Teacher** | Manages courses, grades, and attendance |
| **Student** | Views grades, attendance, GPA, and transcripts |

---

## 🧠 Core Features (Planned)

- Role-based authentication & authorization
- Student enrollment and course management
- Grade entry with weighted assessments
- GPA calculation
- Attendance tracking
- Transcript generation (PDF)
- Academic performance analytics
- Audit logs for grade changes

---

## 🛠️ Tech Stack

- **Frontend**: Next.js (App Router), TypeScript, Tailwind CSS
- **Backend**: Next.js Server Actions
- **Database**: MySQL
- **ORM**: Prisma
- **Authentication**: NextAuth (JWT)
- **Charts**: Recharts / Chart.js
- **PDF Export**: jsPDF / html2canvas

---

## 📁 Project Directory Structure

| Folder               | Purpose                           |
| -------------------- | --------------------------------- |
| `src/app/`           | Routing, layouts, pages           |
| `src/components/`    | Reusable UI components            |
| `src/components/ui/` | Buttons, modals, tables           |
| `src/lib/`           | Utilities (prisma, auth, helpers) |
| `src/server/`        | DB logic & services               |
| `src/actions/`       | Server Actions                    |
