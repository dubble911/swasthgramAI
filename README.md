# SwasthGram Backend

This repository provides a starter backend for the SwasthGram AI frontend. It includes:
- Authentication (JWT)
- Patient CRUD
- Appointment scheduling
- File uploads (local)
- Contact form email

## Quick start
1. Copy `.env.example` to `.env` and fill values.
2. `npm install`
3. `npm run dev` (requires nodemon) or `npm start`

## Notes
- Production: use cloud storage (S3 / GCS) instead of local `uploads/` and secure SMTP credentials.
- Add rate limiting and stricter validation for production readiness.
