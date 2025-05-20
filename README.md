# Personalized-Math-Education-FYP
Personalized Math Education System is a machine learning-based system that automatically generates personalized math exercises based on students' learning progress. Using the Junyi Academy dataset and the DeepMind Math dataset, we used MLP to predict student ability levels (0-4) and generated more than 250,000 exercises
## Function
- Adaptive level system: dynamically assign levels (0-4) based on consecutive correct/incorrect answers.
- Machine Learning Prediction: Predict student ability levels using MLP and LightGBM.
- Feature Engineering: Extract the number of correct answers, total number of questions, consecutive correct answers, and accuracy rate.
- Personalized Exercise Generation: Mapping easy, medium, and hard exercises from the DeepMind dataset.

## Technology Stack
- **Language**: Python
- **Framework**: TensorFlow, Scikit-learn, LightGBM
- **Data processing**: Pandas, NumPy
- **Dataset**: Junyi Academy (16 million records), DeepMind (11.2 million questions)

## Results
- **Model Performance**:
- MLP test accuracy: 85% (vs. 54% for LightGBM). 
- Processed 4.06 million level judgments and generated over 250,000 exercises.
- **Data distribution**: Levels 0 and 4 account for 55%, 1-3 account for 45%, balanced prediction.
- **Application**: Improve students' learning efficiency and is suitable for personalized education platforms.
