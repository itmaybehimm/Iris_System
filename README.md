### Iris Recognition System

This repository contains an Iris Recognition System developed using Python with a focus on Python 3.10 and Django framework for the backend.

#### Setup Instructions

1. **Python Virtual Environment:**

   - Create a virtual environment with Python 3.10:
     ```bash
     python3.10 -m venv venv
     ```

2. **Installation:**

   - Activate the virtual environment:
     ```bash
     source venv/bin/activate  # for Unix/Linux
     venv\Scripts\activate      # for Windows
     ```
   - Install the required packages using pip:
     ```bash
     pip install -r requirements.txt
     ```

3. **Running the Backend:**

   - Navigate to the `backend` directory:
     ```bash
     cd backend
     ```
   - Start the Django server:
     ```bash
     python manage.py runserver
     ```

4. **Train own model:**
   - After training the model, replace weights by naming to current.h5 and .keras to backend/backend

#### Implementation Details

- Implementation details, including architecture, methodologies, and results, can be found in the `report` folder.
- [Segmentation Repository](https://github.com/itmaybehimm/segmentation): For related segmentation functionalities, refer to this repository.

#### Contributors

- [Himanshu Pradhan](https://github.com/itmaybehimm)

Feel free to contribute by opening issues, providing feedback, or submitting pull requests. Thank you for your interest in the Iris Recognition System!
