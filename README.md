# 🚀 FastAPI Basics Project

A simple demonstration and exploration of core concepts in the FastAPI framework, including routing, path parameters, and SQLAlchemy database integration (SQLite).
## ⚙️ Setup and Installation

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/TheCharismaticEngima/FastAPI-Basics.git](https://github.com/TheCharismaticEngima/FastAPI-Basics.git)
    cd FastAPI-Basics
    ```

2.  **Create and Activate Virtual Environment:**
    ```bash
    python -m venv venv  # Creates the environment
    .\venv\Scripts\activate # Activates the environment on Windows CMD/PowerShell
    ```

3.  **Install Dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Run the Server:**
    * **Note:** This command ensures the table is created and the server starts.
    ```bash
    # Execute the server using the python interpreter directly
    .\venv\Scripts\python -m uvicorn main:app --reload
    ```
    ## 🌐 Usage

The API will be available at `http://127.0.0.1:8000`.

* **API Documentation (Swagger UI):** `http://127.0.0.1:8000/docs`
* **API Documentation (ReDoc):** `http://127.0.0.1:8000/redoc`

**Example Endpoints:**
* `POST /users/` - Create a new user.
* `GET /users/{user_id}` - Retrieve a specific user.

* 
