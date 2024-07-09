# Iris Flower Classification Project

## Overview

This project is an Iris Flower Classification system that uses machine learning to classify iris flowers into three species: setosa, versicolor, and virginica. The backend is built using Django, and the machine learning model is developed using Python libraries such as scikit-learn, matplotlib, and numpy.

## Features

- **Machine Learning Model**: Trained using the iris dataset.
- **Web Interface**: Built with Django for user interaction.
- **Data Visualization**: Plotting features of the dataset using matplotlib.
- **API Integration**: REST API for predictions.

## Technologies Used

- **Backend**: Django, Django REST
- **Machine Learning**: scikit-learn, numpy, pandas
- **Data Visualization**: matplotlib, seaborn
- **Frontend**: HTML, CSS

## Installation

### Prerequisites

- Python 3.x
- Django
- Pip

### Steps

1. **Clone the Repository**
   ```sh
   git clone <repository_url>
   cd <repository_directory>
   ```

2. **Create a Virtual Environment**
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install Dependencies**
   ```sh
   pip install -r requirements.txt
   ```

4. **Apply Migrations**
   ```sh
   python manage.py migrate
   ```

5. **Train the Machine Learning Model**
   ```sh
   python train_model.py
   ```

6. **Run the Server**
   ```sh
   python manage.py runserver
   ```

7. **Open the Website**
   Open your web browser and go to `http://127.0.0.1:8000/`.

## Usage

1. **Upload Data**: Use the web interface to upload new iris flower data.
2. **Get Predictions**: Enter flower measurements to get predictions on the species.
3. **Visualize Data**: View visualizations of the dataset features.

## Project Structure

```
.
├── manage.py
├── requirements.txt
├── train_model.py
├── venv/
├── app_name/
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── migrations/
│   ├── models.py
│   ├── tests.py
│   ├── views.py
│   ├── urls.py
│   ├── templates/
│   │   └── ...
│   └── static/
│       └── ...
├── project_name/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
└── ml/
    ├── __init__.py
    ├── iris_classifier.py
    ├── train_model.py
    └── models/
        └── iris_model.pkl
```

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## Contact

For any questions or feedback, please contact [shashhankt@gmail.com].

---

Thank you for using the Iris Flower Classification Project! Enjoy exploring and classifying iris flowers!
