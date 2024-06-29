# E-commerce Inventory Management System

## Setup and Deployment Instructions

### Prerequisites

1. **Python 3.8+**
2. **AWS CLI**
3. **Serverless Framework**

### Local Setup

1. **Clone the repository**:
    ```bash
    git clone <repository_url>
    cd ecommerce_inventory
    ```

2. **Set up a virtual environment**:
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

3. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Run the application**:
    ```bash
    python app.py
    ```

### AWS Deployment

1. **Install Serverless Framework**:
    ```bash
    npm install -g serverless
    ```

2. **Configure AWS CLI**:
    ```bash
    aws configure
    ```

3. **Deploy the application**:
    ```bash
    serverless deploy
    ```

### API Endpoints

- **POST /products**: Create a new product.
- **GET /products**: Retrieve all products.
- **GET /products/{id}**: Retrieve a single product by ID.
- **PUT /products/{id}**: Update a product by ID.
- **DELETE /products/{id}**: Delete a product by ID.
