
# Java File Hider System

This Java-based application provides a secure file management system with user authentication and OTP-based verification. It supports functionalities for hiding and revealing files, managing user data, and secure communication via email. The system includes a command-line interface for user interaction and uses various Java technologies for database operations and email handling.



## Features

- File Management :
  - Hide Files: Store files in the database and delete them from   the local file system.
  - Unhide Files: Restore files from the database to the local file system.
  - View Files: List hidden files associated with a user.
- User Management :
  - User Registration: Allow users to sign up with OTP verification.
  - User Login: Authenticate users with OTP verification.
- OTP Generation and Email :
  - Generate OTP: Create a 4-digit OTP for secure user verification.
  - Send OTP: Send OTPs to users via email using the JavaMail API.
  - User Interaction: Provides options for users to log in, sign up, and manage files.
- Technologies used : 
  - Java, JDBC, JavaMail API, MySQL


