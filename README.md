# AI-Travel-Planner-for-Students
This project is an AI-powered travel planner designed to help students create personalized and budget-friendly itineraries. Users can input their starting location, destination, budget, travel dates, and interests, and the application will generate a detailed itinerary using the Gemini API.

✨ Features
AI-based travel budget prediction using a trained ML model
Multi-page Streamlit application with session state
State-wise cities, food, and hotel recommendations
Daily itinerary generation
Per-day budget calculation
Budget split visualization using charts
Downloadable travel plan in text format
🛠️ Technologies Used
Python
Streamlit
NumPy
Pandas
Joblib
Altair
HTML & CSS (for custom UI styling)
⚙️ How the Application Works
The user starts the application and clicks "Start Planning".
The user enters travel details such as age, state, interests, accommodation type, and number of days.
The ML model predicts the total travel budget.
The app displays:
Total budget
Per-day budget
Daily travel itinerary
Hotel and food suggestions
Budget split chart
The user can download the travel plan as a text file.
🤖 Machine Learning Model
The application uses a pre-trained Machine Learning model (model2.pkl) loaded using Joblib. The model predicts the total travel budget based on user inputs such as age, interests, accommodation type, travel companion, and trip duration.

📂 Project Structure
AI-Student-Travel-Budget-Planner/ │ ├── app.py # Main Streamlit application ├── model2.pkl # Trained ML model ├── README.md # Project documentation ├── requirements.txt # Required Python libraries

▶️ How to Run the Project
Live Demo: https://ai-travel-planner-for-students123aa.streamlit.app/

🧪 Example Use Case
Age: 21
State: Maharashtra
Days: 5
Gender: M
Primary Interest: Beach
Secondary Interest: Shopping
Travel Companion: Solo
Accommodation: Budget
Output:

Total budget prediction
Daily itinerary
Budget Split visualization
Popular Food recommandations on the particular place
Per-day cost
Downloadable travel plan
Author: CH POOJA SREE
