
# Hostel Attendance Tracker

Hostel Attendance Tracker is a mobile-friendly online system developed to manage hostel attendance in a simple and secure way.  
The system replaces paper-based registers and allows attendance to be marked digitally, with automatic report generation and clear attendance insights.

**Live Application:**  
[https://hostel-attendance-tracker-fxze4fcpsrxrmazsykcdfm.streamlit.app/](https://hostel-attendence-tracker.streamlit.app/)

---

## Project Objective

Traditional hostel attendance is manual, time-consuming, and error-prone.  
This project aims to provide a digital attendance system that:

- Reduces manual work  
- Minimizes attendance errors  
- Provides clear attendance reports  
- Improves transparency in hostel attendance management  

---

## Problem Statement

- Attendance is maintained using register books  
- Manual work leads to mistakes  
- Report preparation takes time  
- No clear visibility of student attendance performance  
- Difficult to identify students with low attendance  

---

## Proposed Solution

The Hostel Attendance Tracker provides:

- Digital attendance marking using mobile or computer  
- Role-based access for different users  
- Automatic attendance report generation  
- Secure storage of attendance data in Excel (Google Sheet)  

---

## Key Features

- Role-based login system (Warden, Morning Person, Night Person)  
- Attendance marking using predefined options:
  - Present (P)
  - Absent (A)
  - Leave (L)
  - Sick (S)
  - College/School (SCH/CLG)
  - Official (OI)
- Attendance lock after submission (no edits allowed)  
- Automatic Excel attendance reports  
- Attendance analytics for monitoring  

---

## Attendance Analytics

The system provides:

- Attendance status overview  
- Monthly attendance summary  
- Low attendance identification (below 75%)  
- Best attendance list  

---

## Dataset and Storage

- Attendance data is generated through the application  
- Data is stored securely in Excel / Google Sheets  
- Downloadable attendance reports are available  

---

## System Workflow (High Level)

1. User logs in with assigned role  
2. Attendance is marked for students  
3. Attendance session is locked after submission  
4. Excel attendance report is generated automatically  
5. Attendance analytics are displayed  

---

## Technology Stack

- Programming Language: Python  
- Framework: Streamlit  
- Data Storage: Excel / Google Sheets  
- IDE: VS Code  

---

## Testing Summary

The following were tested successfully:

- Login and role-based access  
- Attendance marking  
- Attendance locking mechanism  
- Report generation  
- Data storage and retrieval  

All test cases passed successfully.

---

## Future Enhancements

- WhatsApp notifications  
- Advanced reporting features  

---

## Conclusion

The Hostel Attendance Tracker provides a simple, secure, and transparent way to manage hostel attendance digitally.  
It reduces manual effort, avoids errors, and gives management clear visibility into attendance records for better decision-making.
