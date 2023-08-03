# React Native Voucher Management Application Challenge

Welcome to our coding challenge! This project is designed to evaluate your skills in creating a fully functional and dynamic mobile application using React Native.

## Introduction

The application you'll be building is designed to manage vouchers, offering features such as purchasing new vouchers and reviewing existing ones. The application will utilize Firebase Authentication for user registrations and logins to ensure secure access.

## The Challenge

Upon successful login, users should be redirected to their dashboard where their avatar, email address, and registration date will be displayed. The application should include the following pages:

1. **Voucher Overview**: This page should display an infinite scrolling list of all the vouchers purchased by the user, enhancing both performance and user experience. Details such as the current balance and the logo of the voucher vendor should be included here. Clicking on a voucher should take the user to a detailed page displaying the current value, voucher code (as a Barcode-128), and the purchase date of the voucher.

2. **Voucher Purchase**: Here, users should be able to create a new voucher for a selected vendor. The voucher should include the following fields: unique voucher code, current value (user input, value between €0.01 and €250), start value (user input, value between €0.01 and €250), creation date, unique vendor ID (reference to the actual vendor), and user ID.

3. **Settings**: This section should allow the user to edit their account settings, such as changing their password or logging out.

In the backend, Firebase Cloud Firestore should be used to store and retrieve vouchers, ensuring that each user can only access and edit their own vouchers.

## Objective

Your task is to build this application according to the provided specifications. We're keen to assess your coding abilities, problem-solving skills, and knowledge of React Native and Firebase. Your ability to write clean, well-structured, and documented code will also be evaluated.

The ultimate goal is not just to create a functional application but to showcase your technical prowess, creativity, and problem-solving skills. So, take your time, plan your approach strategically, and happy coding!
