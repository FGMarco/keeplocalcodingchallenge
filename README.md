React Native Voucher Management Application Challenge

Welcome to our coding challenge! This project aims to assess your expertise in creating a dynamic, fully functional mobile application using React Native.

Introduction

The primary objective of the application is to allow users to manage vouchers. It will provide features for purchasing new vouchers and reviewing previously purchased ones. We're looking to use Firebase Authentication for handling user registrations and logins, thus ensuring secure access to the application.

The Challenge

After successful login, users should be automatically redirected to their dashboard, displaying their avatar, email address, and registration date. Users should be given the option to navigate between the following pages:

Voucher Overview: This page should list all the vouchers purchased by the user in an infinite scrolling list for improved performance and user experience. The current balance and the logo of the voucher's vendor should also be displayed here. Clicking on a voucher should lead the user to a detail page, displaying the current value, the voucher code (presented as Barcode-128), and the voucher's purchase date.
Voucher Purchase: On this page, users should be able to create a new voucher for a selected vendor. The voucher should include fields for a unique voucher code, current value (user input, value between €0.01 and €250), start value (user input, value between €0.01 and €250), creation date, unique vendor ID (reference to the actual vendor), and user ID.
Settings: Here, the user can edit account settings, such as change their password or log out.
Finally, ensure that you use Firebase Cloud Firestore for storing and retrieving vouchers, making sure that users only have access to and can edit their own vouchers.

Objective

Your task is to build this application following the detailed specifications provided. We aim to assess your coding skills, problem-solving abilities, and your understanding of React Native and Firebase technologies. We're also interested in your capability to write clean, well-structured, and documented code.

The goal is not only to create a functional application but also to impress us with your technical skills, creativity, and problem-solving abilities. So, take your time, plan well, and enjoy the process of coding!

Happy coding!
