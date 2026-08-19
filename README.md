# Syed Ammal Arts and Science College – Attendance Management Android App

A Kotlin + Jetpack Compose + Room starter application for:
- Student management
- Lecturer management
- Time-based class/period management
- Attendance marking
- Local attendance storage

## Build
1. Open this folder in Android Studio Ladybug or newer.
2. Allow Gradle to sync.
3. Run on an Android emulator/device.
4. No Firebase account is required for this MVP because data is stored locally with Room.

## Important
The current MVP intentionally keeps the data model simple. For production deployment, add:
- Firebase Authentication for Admin/Lecturer login
- Cloud Firestore for multi-device synchronization
- Role-based security rules
- Student attendance percentage reports
- PDF/Excel export
- Timetable day-of-week support
- Push notifications
- College logo and branding
- Backup/restore

### Time format
Class times are stored as minutes from midnight:
- 9:00 AM = 540
- 10:00 AM = 600
- 1:30 PM = 810

## Suggested production roles
ADMIN: manage college, departments, students, lecturers, subjects, timetable.
LECTURER: view assigned periods and mark/edit attendance.
STUDENT: view own attendance (optional future module).
