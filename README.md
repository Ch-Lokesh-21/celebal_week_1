# React Form with Validation

A React-based form application with client-side validation using Tailwind CSS. This project validates user input fields like names, email, password, phone number, PAN, and Aadhaar numbers, ensuring accurate and secure data submission.

## Features

- **Responsive Design**: Styled with Tailwind CSS for a modern and mobile-friendly interface.
- **Client-Side Validation**:
  - First Name and Last Name must only contain alphabets.
  - Password must be at least 8 characters long and include:
    - At least one lowercase letter.
    - At least one uppercase letter.
    - At least one digit.
    - At least one special character.
  - Email format validation.
  - Phone number with country code validation.
  - PAN and Aadhaar number validation.
- **Dynamic Dropdowns**:
  - Country selection dynamically updates the city options.
- **Password Toggle**: Show or hide password input.
- **Error Display**: Inline error messages for invalid inputs.
- **Submission**: On successful validation, form data is displayed in a table format on the success page.

## Demo

![Form Screenshot](path_to_image)

## Installation and Setup

Follow these steps to run the project locally:

### Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/) (v14+)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Steps

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/Ch-Lokesh-21/celebal_week_1.git
   cd celebal_week_1