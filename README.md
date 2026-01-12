# InventoryPro - Inventory Management System

A full-stack inventory management system built with FastAPI (backend) and React (frontend) that allows users to track, manage, and monitor their product inventory.

## 🚀 Features

- **Product Management**: Add, edit, delete, and view products in your inventory
- **Real-time Updates**: Instantly see changes reflected in the product list
- **Search & Filter**: Quickly find products by ID, name, or description
- **Sorting**: Sort products by ID, name, price, or quantity
- **Responsive Design**: Works seamlessly across desktop and mobile devices
- **Data Persistence**: Products stored in a database with full CRUD operations

## 🛠️ Tech Stack

### Backend
- **FastAPI**: High-performance web framework for building APIs with Python 3.7+
- **SQLAlchemy**: SQL toolkit and Object Relational Mapping (ORM) library
- **PostgreSQL**: Robust relational database for storing product information

### Frontend
- **React**: JavaScript library for building user interfaces
- **Axios**: Promise-based HTTP client for API requests
- **CSS**: Styling with modern layout techniques

## 📋 Prerequisites

- Python 3.7 or higher
- Node.js and npm/yarn
- Git

## 🚀 Installation

### Backend Setup

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```

2. Set up Python virtual environment:
   ```bash
   python -m venv InventoryPro
   ```

3. Activate the virtual environment:
   - On Windows:
     ```bash
     InventoryPro\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source InventoryPro/bin/activate
     ```

4. Install Python dependencies:
   ```bash
   pip install fastapi uvicorn sqlalchemy
   ```

5. Run the backend server:
   ```bash
   uvicorn main:app --reload
   ```
   The backend API will be available at `http://localhost:8000`

### Frontend Setup

1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```
   The frontend will be available at `http://localhost:3000`

## 🔧 API Endpoints

| Method | Endpoint          | Description                 |
|--------|-------------------|-----------------------------|
| GET    | `/products`       | Get all products            |
| GET    | `/products/{id}`  | Get a specific product      |
| POST   | `/products`       | Add a new product           |
| PUT    | `/products/{id}`  | Update an existing product  |
| DELETE | `/products/{id}`  | Delete a product            |

## 📝 Usage

1. Start both the backend and frontend servers
2. Access the application at `http://localhost:3000`
3. Use the form to add new products to your inventory
4. View, edit, or delete existing products as needed
5. Use the search bar to find specific products
6. Click on table headers to sort products by different criteria

## 🧪 Available Scripts

In the `frontend` directory, you can run:

- `npm start` - Runs the app in development mode
- `npm test` - Launches the test runner
- `npm run build` - Builds the app for production



