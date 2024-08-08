# ReachInbox Assignment - Frontend Engineer

## Project Overview

This project is part of the hiring process for the Associate - Frontend Engineer position at ReachInbox.ai. The assignment involves developing a web application based on provided designs and APIs, focusing on functionalities like login, data fetching, keyboard shortcuts, and a custom text editor.

## Project Structure

├── public/ # Static files like images, icons, etc.
├── src/
│ ├── components/ # Reusable React components
│ ├── pages/ # Pages like Login, Onebox
│ ├── styles/ # CSS and Tailwind styles
│ ├── utils/ # Utility functions and API integrations
│ └── App.js # Main application component
├── .gitignore # Git ignore file
├── package.json # Project dependencies and scripts
└── README.md # Project documentation

## Features Implemented

1. **Login Page**
   - Developed the login page using the provided Figma design.
   - Redirects users to the Onebox screen upon successful login.

2. **Onebox Screen**
   - Fetched data from the provided API and displayed it in the Onebox screen.
   - Implemented the following API routes:
     - `GET /onebox/list`
     - `GET /onebox/:thread_id`
     - `DELETE /onebox/:thread_id`

3. **Keyboard Shortcuts**
   - Added keyboard shortcuts in the Onebox screen:
     - Pressing “D” deletes a thread.
     - Pressing “R” opens the reply box.

4. **Custom Text Editor**
   - Integrated a custom text editor with additional buttons such as “SAVE” and “Variables”.

5. **Reply Functionality**
   - Implemented the reply feature:
     - `POST /reply/:thread_id`
     - The request includes sender and receiver emails, subject, and email body.

6. **Light and Dark Mode**
   - Implemented both light and dark themes with a toggle option.

## Setup and Installation

### Prerequisites

- **Node.js** (version 14 or higher)
- **npm** or **yarn**

### Installation Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/reachinbox-assignment.git
   cd reachinbox-assignment
Install dependencies


npm install


Run the development server
npm run dev

