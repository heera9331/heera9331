# ✉️ Temporary Email Web App

## 📌 Overview

This project involved developing a temporary email web application that generates disposable email addresses for users and delivers incoming emails in real-time. The goal was to provide a fast, secure, and easy-to-use service to help users avoid spam and protect their privacy.

## 📅 Project Timeline

- Start Date: 07-01-2024
- Completion Date: 01-01-2025
- Live Link: https://moohmal.com
- Live Link2: https://correo-temporall.com

## Technologies Used

- Next.js (Frontend)
- Node.js (Backend)
- Socket.IO (Real-time communication)
- IMAP (Email fetching)
- Custom Server (Handling request routing and real-time updates)

## 🔍 Challenges & Solutions

**🛠 Real-Time Email Delivery**

The app needed to deliver emails in real-time as they arrived in the inbox.
Used Socket.IO to establish a persistent connection and push new emails to the frontend immediately upon arrival.

**🛠 IMAP Configuration & Handling**

Setting up IMAP to fetch emails was complex due to authentication and mailbox state issues.
Configured IMAP to connect securely and handle new mail events efficiently without losing connection.

**🛠 Email Parsing & Formatting**

Incoming emails had to be parsed and displayed properly, including HTML content and attachments.
Built a custom email parsing function to clean up formatting and ensure correct display of different email types.

**🚀 Key Learnings & Takeaways**

- Real-time communication using Socket.IO.
- Secure email handling with IMAP.
- Building a custom server with Next.js and Node.js.
- Handling complex email parsing and real-time updates efficiently.
- This project highlights my expertise in real-time data handling, secure email processing, and creating a seamless user experience through advanced server-client communication.
