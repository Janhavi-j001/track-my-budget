Here’s the updated README file reflecting the change from `npm run start` to `npm run dev` for running the development server:

---

# TrackMyBudgets: Budgets and Expenses Tracking Web App

TrackMyBudgets is a progressive web application that helps users manage and track their personal budgets and expenses. With features like multiple budget creation, expense categorization, and progress visualization, the app provides a seamless way to take control of your finances.

---

## Features

- **Multiple Budgets:** Create and manage multiple budgets for different financial goals.
- **Expense Categorization:** Add and organize expenses under custom or predefined categories.
- **Progress Visualization:** View budget utilization with dynamic charts and summaries.
- **Responsive Design:** Fully responsive and functional on desktop, tablet, and mobile devices.
- **Real-Time Feedback:** Interactive notifications using Toastify for enhanced user experience.
- **LocalStorage Integration:** Securely store data locally for offline use.

---

## Live Demo

Explore the app here: [TrackMyBudgets Live Demo](https://trackmybudgets.netlify.app)

---

## Technologies Used

- **React**: Core framework for building the app's UI.
- **React Router**: For handling multi-page navigation without reloading the app.
- **CSS**: For styling, layout, and responsive design.
- **LocalStorage**: To persist data locally for offline use.
- **Toastify**: To provide user-friendly notifications and alerts.

---

## Installation and Setup

Follow these steps to set up and run the project locally:

### Prerequisites

- [Node.js](https://nodejs.org/) (v14 or higher recommended)
- [npm](https://www.npmjs.com/) or [Yarn](https://yarnpkg.com/) package manager

### Installation Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/janhavi-j001/track-my-budget.git
   cd track-my-budget
   ```

2. **Install Dependencies**
   Run the following command to install all necessary dependencies:
   ```bash
   npm install
   ```

3. **Start the Development Server**
   Run the application locally:
   ```bash
   npm run dev
   ```

4. **Build the App for Production**
   If you want to build the app for production, run:
   ```bash
   npm run build
   ```

5. **Access the App**
   Open your browser and navigate to:
   ```
   http://localhost:3000
   ```

---

## Folder Structure

```bash
track-my-budgets/
├── public/          # Static files (HTML, favicon, etc.)
├── src/
│   ├── components/  # Reusable React components
│   ├── pages/       # Page-level components
│   ├── assets/      # Images, icons, etc.
│   └── App.js       # Main application logic
├── package.json     # Project metadata and dependencies
└── README.md
```
