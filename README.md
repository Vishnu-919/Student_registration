# Student Registration Form

This project is a basic HTML form that allows students to register by entering their personal and academic details. The form includes fields for name, roll number, email, gender selection, and branch selection.

## 🚀 Features

- Text input fields for name, roll number, and email
- Email input uses built-in HTML5 validation
- Gender selection using radio buttons
- Branch selection using a dropdown menu
- Form submission using POST method

## 📄 Form Fields

| Field         | Type         | Description                        |
|---------------|--------------|------------------------------------|
| Student Name  | Text         | Full name of the student           |
| Roll Number   | Text         | Unique student roll number         |
| Email         | Email        | Student's email address            |
| Gender        | Radio Button | Select Male, Female, or Other      |
| Branch        | Dropdown     | Choose from available branches     |

## 📤 Form Submission

- **Method**: POST  
- **Action URL**: `/submit` (You need to implement this server-side route)

## 🛠 How to Use

1. Open `index.html` in any web browser.
2. Fill in the student details.
3. Click **Submit**.
4. The form data will be sent to the `/submit` endpoint.

> ⚠️ Note: This form requires a backend server to handle form submissions at the `/submit` URL.

## 🧪 Example Branch Options

- Information Technology (`IT`)
- Electronics and Communication Engineering (`ECE`)

## ✅ Browser Compatibility

This form uses standard HTML5 and works in all modern browsers.

## 📁 File Structure

