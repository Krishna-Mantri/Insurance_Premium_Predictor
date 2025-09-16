# Insurance Premium Predictor

A Machine Learning based Insurance Premium Predictor project built to estimate insurance premiums based on a specific dataset.

---

## About The Project

The Insurance Premium Predictor leverages machine learning techniques to predict insurance premium amounts accurately. It uses a specific dataset related to insurance cases and applies data processing and predictive modeling to forecast premium costs. This tool aids users and companies in understanding and estimating insurance premiums effectively, facilitating better decision-making in the insurance domain.

---

## Features

- Predict insurance premiums using machine learning models.
- Data-driven approach for accurate and reliable premium estimation.
- Built with a modern FastAPI backend for scalable and high-performance API services.
- Easily extensible to adapt to other datasets or insurance-related prediction tasks.

---

## Tech Stack

| Category            | Technology / Library          | Description                                               |
|---------------------|------------------------------|-----------------------------------------------------------|
| **Backend Framework**| FastAPI                      | High-performance Python web framework to build REST APIs |
| **ASGI Server**      | Uvicorn                     | ASGI server for running FastAPI applications              |
| **Data Validation**  | Pydantic                    | Data parsing and validation library used by FastAPI       |
| **Machine Learning** | scikit-learn                | Library for predictive modeling and ML algorithms         |
| **Data Processing**  | numpy                       | Numerical computing library                                |
|                      | pandas                      | Data manipulation and analysis library                      |
| **Web Framework**    | starlette                   | ASGI framework used by FastAPI                             |

---

## Getting Started

### Prerequisites

- Python 3.x installed on your machine.
- All dependencies listed in `requirements.txt`.

### Installation

1. Clone the repository  
git clone https://github.com/Krishna-Mantri/Insurance_Premium_Predictor.git

2. Navigate to the project directory:  
cd Insurance_Premium_Predictor

3. Install the required dependencies:  
pip install -r requirements.txt


### Running the Application

Start the FastAPI server using Uvicorn (update `main:app` with the actual app path if different):
uvicorn main:app --reload


The API will be available at `http://127.0.0.1:8000`.

---

## Usage

Use the API endpoints to input customer details and get insurance premium predictions. Documentation for the API endpoints is automatically generated and accessible at:

http://127.0.0.1:8000/docs


---

## Contributing

Contributions are warmly welcomed! Feel free to:

- Open issues to report bugs or suggest features.
- Submit pull requests to improve the project.

Please ensure that your code follows the existing style and passes any tests before submitting.

---

## Contact

For questions, suggestions, or support, please open an issue in this repository.

---

## Acknowledgements

Thanks to all contributors and to the open-source community for the tools and libraries powering this project.

---
