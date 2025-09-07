📝 Overview

HousePriceAI helps users predict Melbourne house prices using a machine learning model. The project uses a Linear Regression model trained on real housing data, with a React frontend for smooth user interaction and a Flask backend for serving predictions.

The backend is hosted on Hugging Face Spaces, and the frontend is deployed on Netlify, making it accessible online without requiring any database.

✨ Features

🏡 Predict house prices in Melbourne based on property features (bedrooms, bathrooms, land size)

💻 Modern and responsive UI using React and Tailwind CSS

⚡ Fast predictions powered by a Linear Regression ML model

🌐 Fully deployed and accessible online

🛠 Technologies Used

Frontend:

⚛️ React

🎨 Tailwind CSS (via CDN)

Backend:

🐍 Python

🔧 Flask

Machine Learning:

📈 Linear Regression (scikit-learn)

Deployment:

🌐 Frontend: Netlify

🖥 Backend & ML model: Hugging Face Spaces









🔗 Live Demo: https://phenomenal-capybara-8aeee5.netlify.app/

⚙️ How It Works

The user opens the web app and enters property details (bedrooms, bathrooms, land size, etc.).

The React frontend sends the input data to the Flask backend API hosted on Hugging Face Spaces.

The backend loads the trained Linear Regression model and predicts the house price.

The prediction is sent back to the frontend and displayed instantly.

💻 Installation

Clone the repository:

    git clone https://github.com/your-username/HousePriceAI.git
    cd HousePriceAI


Setup Backend:

    cd house-price-backend
    pip install -r requirements.txt
    python app.py


Setup Frontend:

    cd frontend
    cd house-price-app
    npm install
    npm start

🚀 Usage

Open the web app (locally or via Netlify Deployment).

Enter property details like bedrooms, bathrooms, and land size.

Click Predict to see the estimated house price.

Get results instantly on the screen.

📸 Screenshots

Home Page: <img width="947" height="444" alt="image" src="https://github.com/user-attachments/assets/e2d6457b-7405-4f76-b664-a42a4f28eb7c" /> 

Prediction Page: <img width="931" height="507" alt="image" src="https://github.com/user-attachments/assets/cb74b00b-52e7-430c-bb8e-0508cd8ea81e" />

Example Prediction: <img width="946" height="470" alt="image" src="https://github.com/user-attachments/assets/0eabae5a-eeb7-4faa-8da6-bc2cb232cb7a" />

About me: <img width="935" height="499" alt="image" src="https://github.com/user-attachments/assets/3d835e2d-7e90-461b-8460-5d0e1e36aa06" />

🤝 Contributing

Contributions are welcome!

Fork the repository

Make your changes

Submit a pull request

📄 License

This project is licensed under the MIT License.

✅ Live Demo: https://phenomenal-capybara-8aeee5.netlify.app/
