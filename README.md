Chatbot for Health Awareness

A healthcare-focused chatbot system designed to provide users with quick and accurate information about potential diseases based on their symptoms. This project aims to reduce healthcare costs and improve accessibility by offering preliminary diagnoses and personalized suggestions before consulting a doctor.


Features
Symptom Analysis: Users input symptoms in text form, and the chatbot identifies relevant diseases using natural language processing (NLP).
Disease Classification: Categorizes diseases as major or minor based on symptoms and suggests doctors for severe conditions.
Recommendations: Provides analgesic suggestions and food recommendations tailored to the user's condition.
User-Friendly Interaction: Supports natural conversations with responses based on keyword matching and NLP algorithms.


Technologies Used
Python: For backend development and core functionality.
NLP Algorithms: Includes N-grams, TF-IDF, and Cosine Similarity for symptom matching and disease identification.
Flask: A lightweight web framework for building the chatbot interface.
HTML, CSS, JavaScript: For creating a responsive and interactive user interface.
SQL: To store and retrieve user data, symptoms, and doctor information.


How It Works
Users interact with the chatbot via text input.
The system extracts keywords from the input using NLP algorithms and matches them with the trained dataset.


Based on the analysis:
Provides disease classification (major/minor).
Suggests relevant doctors and treatment options.
Offers dietary and medication advice.


Challenges Faced
Handling varied user inputs with natural language complexities.
Ensuring accurate disease mapping using a limited dataset.
Balancing user-friendliness with technical precision in symptom diagnosis.


Key Learning Outcomes
Practical implementation of NLP techniques for real-world healthcare problems.
Building a scalable chatbot using Flask and integrating it with a relational database.
Enhancing user interaction through optimized response generation.


Future Enhancements
Adding voice interaction for accessibility.
Expanding the dataset to include more diseases and symptoms.
Integrating a scheduling feature for doctor appointments.


How to Run
Clone the repository:
git clone https://github.com/yourusername/health-awareness-chatbot.git

Install the required dependencies:
pip install -r requirements.txt

Run the Flask application:
python serve.py

Access the chatbot interface at  http://127.0.0.1:5000 in your browser.
