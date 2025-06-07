# React Form with Validation Without Third-Party Libraries

A React-based form application that implements client-side validation without the use of third-party libraries. The application ensures all required fields are validated before submission and displays the form details on a new route upon successful submission.

---

## Features

1. **Validation for Required Fields**: Ensures that all mandatory fields are correctly filled before enabling the form submission.
2. **Real-Time Error Messages**: Displays appropriate error messages as users input invalid data.
3. **Show/Hide Password**: A toggle button to show or hide the password.
4. **Dynamic Dropdowns**: Country and city fields dynamically update based on the user's selection.
5. **Field-Specific Validations**:
   - **First Name & Last Name**: Alphabets only.
   - **Email**: Must include "@".
   - **Password**: At least 8 characters with one uppercase, one lowercase, one number, and one special character.
   - **Phone Number**: Format as `+CountryCode Number`.
   - **PAN & Aadhar Numbers**: Validated using specific patterns.
6. **Submission Redirect**: Displays submitted details in a structured table on a new route after successful submission.

---

## Live Demo

[Live Demo Link](#) *(Replace `#` with the actual URL)*

---

## Screenshots

### 1. Form Page
![Form_Page_1](https://github.com/Ch-Lokesh-21/celebal_week_1/blob/cd9bad8ad504275826d4f6be0b439ebe0f2763d5/Screenshot%202025-06-08%20010039.png)

![Form_Page_2](https://github.com/Ch-Lokesh-21/celebal_week_1/blob/cd9bad8ad504275826d4f6be0b439ebe0f2763d5/Screenshot%202025-06-08%20004240.png)

![Form_Page_3](https://github.com/Ch-Lokesh-21/celebal_week_1/blob/219b114e2e180bf8cc52e5591a93d8f70e0ae1ae/Screenshot%202025-06-08%20010519.png)

*Description: This screenshots shows the form with various fields, real-time validation, and error messages.*

### 2. Success Page
![Success_Page](https://github.com/Ch-Lokesh-21/celebal_week_1/blob/cd9bad8ad504275826d4f6be0b439ebe0f2763d5/Screenshot%202025-06-08%20004302.png)  

*Description: This screenshot displays the structured table with all submitted details.*

---

## Technologies Used

- React
- Tailwind CSS
- React Router DOM

---

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/Ch-Lokesh-21/celebal_week_1.git
   cd celebal_week_1
2. Install dependencies:
    ```bash
    npm install
3. Run the development server:
    ```bash
    npm run dev
