# **Quizzler**

## **Overview**
Welcome to Quizzler, the trivia quiz application designed to make learning fun and efficient! As a student, I often wished for a tool that could enhance my study sessions with engaging content. Quizzler transforms mundane revision into an interactive experience, utilizing natural language processing (NLP) techniques to analyze and present trivia questions dynamically. Built with **Python** and **Tkinter**, and powered by the **Open Trivia Database API**, this app enables users to learn quickly while enjoying the challenge of trivia.

## **Features**
- **Dynamic Question Retrieval**: Uses the Open Trivia Database API to fetch diverse trivia questions in real-time, employing NLP to parse and present questions effectively.
- **User-Friendly Interface**: Built with Tkinter, ensuring intuitive navigation for users of all ages.
- **Score Tracking**: Monitors user performance, providing instant feedback and utilizing sentiment analysis to enhance the learning experience.
- **Modular Design**: Organized code structure allows for easy updates, ensuring adaptability for future enhancements.

## **Installation**
To get started with Quizzler, follow these steps:
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/TejasUpadhyayy/Quizzler.git
   ```
2. **Navigate to Project Directory**:
   ```bash
   cd Quizzler
   ```
3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
4. **Run the Application**:
   ```bash
   python main.py
   ```

## **Project Structure**
```
.
├── data/                   # Contains trivia data files
├── quiz_brain.py           # Core logic for quiz functionality
├── question_model.py       # Data model for quiz questions
├── ui.py                   # User interface setup using Tkinter
├── main.py                 # Main script to run the application
├── README.md               # Project documentation
└── requirements.txt        # Dependencies needed for the project
```

## **Usage**
1. **Launch the Application**: Execute `main.py` to start the application.
2. **Answer Questions**: Engage with true/false questions, making quick selections.
3. **Track Your Score**: The application dynamically updates and displays your score, using NLP techniques to provide tailored feedback based on user performance.

## **Future Improvements**
- **Enhanced Question Categories**: Implement support for multiple categories and subcategories, allowing users to tailor their quiz experience.
- **Adaptive Difficulty Levels**: Introduce algorithms that adjust question difficulty based on user performance, using machine learning techniques to enhance engagement.
- **Interactive Question Formats**: Expand the application to support multiple-choice questions and timed challenges, utilizing NLP to analyze user responses and improve question quality.

## **Contributing**
Contributions to Quizzler are highly encouraged! Here’s how you can get involved:
1. **Fork the Repository**: Create your own copy of the project.
2. **Branch for Your Feature**: Make sure to create a new branch for your feature or bug fix:
   ```bash
   git checkout -b feature/YourFeatureName
   ```
3. **Make Your Changes**: Implement your improvements or new features, ensuring your code is well-documented.
4. **Commit Your Changes**: Write clear, concise commit messages describing your changes:
   ```bash
   git commit -m "Add new feature or fix bug"
   ```
5. **Push to Your Branch**:
   ```bash
   git push origin feature/YourFeatureName
   ```
6. **Create a Pull Request**: Submit your changes for review. Provide a detailed description of what you’ve implemented and why it’s beneficial.

---

## **Contact**
- **Developer**: Tejas Upadhyay, Mobashir Ali, Aadarsh Dubey, Hardik Sharma, Ritesh Sahoo
- **GitHub**: [TejasUpadhyayy](https://github.com/TejasUpadhyayy/Quizzler)

