# Community Rooms

[![MIT License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![Python Version](https://img.shields.io/badge/python-3.9-blue)
![Made with Love](https://img.shields.io/badge/Made%20with-%E2%9D%A4-red)

This small project is a beginners approach to create a platform for users to create, join, and interact in virtual study rooms.

## Setup Instructions

Follow these steps to set up and run the project on your local machine.

### 1. Clone the Repository
First, clone the repository from GitHub using the following command:
```bash
git clone https://github.com/AryanKaushal2002/community_rooms.git
```

### 2. Ensure Python 3.9.x is Installed
This project requires **Python 3.9.x** due to a dependency on Pillow, which works best with this version. Ensure that your virtual environment is set up with Python 3.9.x or equivalent.

You can check your Python version with the following command:
```bash
python --version
```

If you have multiple versions of Python installed, you can specify Python 3.9 when creating the virtual environment.

### 3. Create a Virtual Environment
To create a virtual environment, you'll need `virtualenv`. If you don't have it installed, you can install it via `pip`:
```bash
pip install virtualenv
```

Once installed, create a virtual environment using Python 3.9.x:
```bash
virtualenv -p python3.9 .venv
```

### 4. Activate the Virtual Environment
Activate the virtual environment using the following command:

- On Windows:
    ```bash
    .venv\Scripts\activate
    ```

- On macOS/Linux:
    ```bash
    source .venv/bin/activate
    ```

### 5. Install Dependencies
Install all the required dependencies from the `requirements.txt` file:
```bash
pip install -r requirements.txt
```

### 6. Navigate to the StudyBud Folder
Once dependencies are installed, navigate to the `studybud` folder:
```bash
cd studybud
```

### 7. Run the Development Server
Run the Django development server to start the application:
```bash
python manage.py runserver 8081
```

The site will now be running locally on `http://127.0.0.1:8081/`.
