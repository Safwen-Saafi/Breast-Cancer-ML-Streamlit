# ⚠️ Breast Cancer Prediction Web App ⚠️

A web application that predicts whether a breast cell cluster is benign or malignant based on multiple features. The app provides a user-friendly interface with a circular chart that updates dynamically based on user input and a result display showing the probability of each case.

## Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)

  
![Capture d'écran 2024-08-04 154333](https://github.com/user-attachments/assets/1b8cd9fb-2773-45c2-a21c-cbd1bfc56a55)

## Features

- **Dynamic Circular Chart**: Visual representation of input features that updates in real-time.
- **Result Display**: Shows the prediction result with probabilities for benign and malignant cases.
- **User-Friendly Interface**: Simple and intuitive interface for easy data input and result interpretation.

# ⬇️⬇️ Live Demo here  ⬇️⬇️

## Check out the live demo [here](https://breast-cancer-ml-app-q.streamlit.app/).
<br/>
![Capture d'écran 2024-08-04 154314](https://github.com/user-attachments/assets/ba676b4a-44ee-447f-9ae3-ce331d4550fe)




## Installation

To set up and run this project locally, follow these steps:

1. **Clone the repository**:
   ```sh
   git clone https://github.com/Safwen-Saafi/Breast-Cancer-ML-Streamlit.git
2. **Navigate to the project directory**:
   ```sh
   cd Breast-Cancer-ML-Streamlit
3. **Activate your Conda environment**:
   ```sh
   conda activate your_env_name
4. **Install the required packages**:
   ```sh
   conda install --file requirements.txt
5. **Run the application**:
   ```sh
   cd app
   streamlit run main.py
## Usage

1) **Input Features**: Use the sliders in the sidebar to input measurements of cell nuclei.
2) **Visualize Data**: The circular chart will update dynamically to reflect your inputs.
3) **View Prediction**: The result window on the right displays the prediction (Benign or Malignant) and the probability of each case.





## Technologies Used
- **Python**: Programming language used for backend development.
- **Streamlit**: Framework for building the web interface.
- **Scikit-learn**: Machine learning library used for building the prediction model.
- **Pandas**: Data manipulation and analysis library.
- **NumPy**: Library for numerical computations.
- **Matplotlib**: Plotting library for visualizations.
- **Pickle**: For model serialization and deserialization.




<p align="center">Developed with ❤️ by SafSaf</p>
