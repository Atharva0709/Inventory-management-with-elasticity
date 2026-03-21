
# Inventory Management

A comprehensive inventory management system designed to optimize supply chain operations with elasticity. The platform is divided into a robust server-side backend and a modern, responsive frontend.

## Features

* **Inventory Tracking:** Monitor and manage stock levels efficiently in real-time.
* **Elasticity:** Adapt to changes in demand and supply dynamically.
* **Analytics:** Gain actionable insights into inventory trends and system performance.
* **Market Sensing:** Predict market trends and adjust inventory parameters accordingly.
* **User Authentication:** Secure access control with reliable login and logout functionality.

---

## Project Structure

The project directory is split into two primary environments:

**Backend Environment**
Located in the `backend/` directory, this handles server-side logic, APIs, and database interactions. 
* **`backend/api/index.js`**: Entry point for API routes.
* **`backend/package.json`**: Backend dependencies and run scripts.
* **`backend/vercel.json`**: Configuration for serverless deployment on Vercel.

**Frontend Environment**
Located in the `frontend/` directory, this is a React and TypeScript application built with Vite.
* **`frontend/src/`**: Core application logic containing UI components, pages, custom hooks, and utility functions.
* **`frontend/public/`**: Static assets such as images and icons.
* **`frontend/vite.config.ts`**: Configuration settings for the Vite bundler.
* **`frontend/tailwind.config.js`**: Styling configuration for Tailwind CSS.

---

## Getting Started

**Prerequisites**
* Node.js (v16 or higher)
* npm (or yarn)

**Installation**
1. Clone the repository:
   ```bash
   git clone [https://github.com/Atharva0709/Inventory-management-with-elasticity.git](https://github.com/Atharva0709/Inventory-management-with-elasticity.git)
   ```
2. Navigate to the project root:
   ```bash
   cd Inventory-management-with-elasticity
   ```
3. Install the backend dependencies:
   ```bash
   cd backend && npm install
   ```
4. Install the frontend dependencies:
   ```bash
   cd ../frontend && npm install
   ```

---

## Running the Application

To run the full stack locally, you will need to start both servers in separate terminal windows.

**Start the Backend Server**
```bash
cd backend
npm start
```

**Start the Frontend Server**
```bash
cd frontend
npm run dev
