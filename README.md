<body>
    <div class="container">
        <h1>🩺 OncoVision: Breast Cancer Prediction System</h1>
        <h2>Overview</h2>
        <p class="animated">Welcome to the <b>Breast Cancer Prediction System</b>, a comprehensive web application that predicts whether a tumor is <b>Malignant</b> or <b>Benign</b> based on user input. This system uses advanced machine learning algorithms and presents results interactively through visual representations like <b>Pie Charts</b> and a user-friendly interface.</p>
        <h2>✨ Key Features</h2>
        <ul>
            <li>Frontend: Home Page, About Page, Predictor Page, User Dashboard, Registration Page, Login Page, Recommendation Page, Subscription for Newsletters (via Email)</li>
            <li>Backend: Flask for seamless web service operations, integration of machine learning models for real-time prediction</li>
            <li>Chatbot: <b>MammoMate</b>, the AI-powered chatbot for breast cancer-related queries</li>
        </ul>
        <h2>💻 Frontend Tech Stack</h2>
        <ul>
            <li>HTML5/CSS3/JavaScript</li>
            <li>Bootstrap for responsiveness</li>
            <li>GSAP & Locomotive Scroll for smooth animations</li>
            <li>Chart.js for visualizing prediction results</li>
        </ul>
        <p>Each page of the website offers a clean, stylish, and responsive design:</p>
        <ul>
            <li><b>Home Page:</b> The homepage introduces the application with seamless animations and navigations.</li>
            <li><b>About Page:</b> Information about breast cancer and its early detection methods.</li>
            <li><b>Predictor Page:</b> An interactive user input form for prediction with live result visualization.</li>
            <li><b>User Dashboard:</b> A dashboard for users to view their prediction history and other details.</li>
            <li><b>MammoMate:</b> The chatbot provides interactive AI-based responses to breast cancer-related queries.</li>
            <li><b>Registration/Login:</b> Users can register and log in for personalized experience.</li>
            <li><b>Subscription Section:</b> Users who subscribe receive periodic newsletters via email about the latest in breast cancer research and treatment.</li>
        </ul>
        <h2>🔥 Backend Tech Stack</h2>
        <ul>
            <li>Flask Framework for backend logic</li>
            <li>Jinja Templating Engine for rendering dynamic content</li>
            <li>Machine Learning Algorithms for real-time prediction</li>
            <li>REST API for handling prediction requests</li>
        </ul>
        <h3>Backend Flow:</h3>
        <ul>
            <li>Flask receives user input from the predictor page.</li>
            <li>The machine learning model processes the input and calculates a prediction score.</li>
            <li>The result is dynamically rendered as 'Cancer' or 'No Cancer' along with a percentage-based pie chart showing Malignant vs Benign predictions.</li>
        </ul>
        <h2>📊 Data Science & Machine Learning</h2>
        <ul>
            <li>Python3 for backend data handling</li>
            <li>Pandas & NumPy for data manipulation</li>
            <li>scikit-learn & TensorFlow for machine learning model creation</li>
            <li>Matplotlib for backend visualizations</li>
        </ul>
        <p>The model was trained on historical breast cancer datasets to predict malignant or benign outcomes based on medical parameters such as Area Worst, Concave Points Worst, Radius Worst, and more. Predictions are served via Flask, and the result is displayed in a pie chart showing the percentage distribution of Malignant vs Benign predictions.</p>
        <h2>📬 Email Subscription System</h2>
        <p>If users subscribe by entering their email address on our website:</p>
        <ul>
            <li>They will receive a confirmation email.</li>
            <li>Periodic newsletters will be sent regarding updates in breast cancer research and treatment options.</li>
        </ul> 
        <h2>📁 Project Structure</h2>
       <pre>
 AI-Treatment-with-Breast-Cancer/
├── OncoVision/                      
│   ├── app.py                    
│   ├── requirements.txt          
│   └── model/                    
│       ├── logistic_regression_model.pkl  
│       └── scalar.pkl
    ├── templates/                     
│       ├── home.html                
│       ├── about.html
        ├── dashboard.html
│       ├── howitworks.html
│       ├── login.html
│       ├── predictor.html
│       ├── recommendations.html     
│       └── register.html
    ├── instance                     
│       └── users.db
├── data/                         
│   ├── BCP - Logistic Regression.ipynb
│   └── ML Project with Logistic Regression.ipynb      
├── README.md                     
└── LICENSE                       
     
</pre>

<h2>🚀 How to Run the Project</h2>
        <ol>
            <li>Clone the repository:
                <pre><code>git clone https://github.com/your-repo-name.git</code></pre>
            </li>
            <li>Set up the environment and install dependencies:
                <pre><code>pip install -r requirements.txt</code></pre>
            </li>
            <li>Run the Flask application:
                <pre><code>python app.py</code></pre>
            </li>
        </ol>
</body>
