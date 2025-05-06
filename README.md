# El-Forsan E-commerce

El-Forsan E-commerce is a full-stack web application that offers a seamless online shopping experience. Built with React.js for the frontend and Django for the backend, this platform provides robust features for both customers and administrators.

## 🌐 Live Demo

Experience the live application here: [elforsanolive.com](https://elforsanolive.com/)

## 📖 Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## ✨ Features

- **User Authentication**: Secure login and registration system.
- **Product Management**: Admins can add, update, and delete products.
- **Shopping Cart**: Users can add products to their cart and proceed to checkout.
- **Order Tracking**: Users can track their orders and view order history.
- **Responsive Design**: Optimized for various devices and screen sizes.

## 🛠️ Tech Stack

- **Frontend**: React.js, JavaScript, CSS
- **Backend**: Django, Python
- **Database**: SQLite (default), can be configured to use PostgreSQL or MySQL

## 🚀 Installation

### Prerequisites

- Python 3.x
- Node.js and npm
- Git

### Backend Setup

1. **Clone the repository**:

   ```bash
   git clone https://github.com/mahmoud-saed/El-Forsan-e-commerce.git
   cd El-Forsan-e-commerce/backend
   ```

2. **Create a virtual environment**:

   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```

3. **Install dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

4. **Apply migrations**:

   ```bash
   python manage.py migrate
   ```

5. **Create a superuser**:

   ```bash
   python manage.py createsuperuser
   ```

6. **Run the development server**:

   ```bash
   python manage.py runserver
   ```

   The backend will be available at [http://localhost:8000](http://localhost:8000).

### Frontend Setup

1. **Navigate to the frontend directory**:

   ```bash
   cd ../frontend
   ```

2. **Install dependencies**:

   ```bash
   npm install
   ```

3. **Start the development server**:

   ```bash
   npm start
   ```

   The frontend will be available at [http://localhost:3000](http://localhost:3000).

## 📸 Usage

- **Home Page**: Browse featured products and categories.
- **Product Details**: View detailed information about a product.
- **Shopping Cart**: Add products to your cart and proceed to checkout.
- **User Profile**: Manage your account information and view order history.
- **Admin Panel**: Admins can manage products, orders, and users.

## 📁 Project Structure


```plaintext
El-Forsan-e-commerce/
├── backend/
│   ├── manage.py
│   ├── el_forsan/
│   └── ...
├── frontend/
│   ├── public/
│   ├── src/
│   └── ...
├── README.md
└── ...
```


## 🤝 Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.
