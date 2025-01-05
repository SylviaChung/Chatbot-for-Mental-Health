# Chatbot-for-Mental-Health
This is an interactive mental health chatbot create by Python.
# Code Structure
There are 4 Class : Class Physical Health Advice, Class Mental Health , Class Social Health and Class Behavioral Health

-- For Class Physical Health Advice : 
4 methods - sleep 1, nutrition 2, exercise 3, BMI 4, each method with the same structure. Let’s use ‘sleep’ as an example here. We store the user’s rating for their sleep quality in a dictionary named responses, which is linked with the current instance of the class. This will enable the chatbot to remember the user's previous responses.
Then we use the if and elif to evaluate the rating provided by the user. If the user types ‘3’, the chatbot will return ‘your sleep quality is neutral, try to create a bedtime routine, and don't use electronics right before sleep.’

--For  Class Mental Health:
‘topic’ attribute in the Mental Health class to store key questions for each mental health dimension. 'topic' include 'sleep', 'anxiety', 'mood', 'stress', 'energy'

The main method used: the analyze_input method , which aims at analysing user input: identifying keywords in the user's answers, matching predefined patterns and returning the corresponding feedback

--For Class Social Health:
focuses on five key dimensions of social well-being, such as “interaction frequency”, “emotional openness”, “social engagement”, “support networks”, and “boundary management”.

--For Class Behavioral Health:
analyze the lifestyle and patterns ("passive aggressive tendencies", "hostility", "codependency traits")

# Result of the Chatbot
![image](https://github.com/user-attachments/assets/af99194f-bc3f-4b08-a7bb-2da567e3a4ff)
![image](https://github.com/user-attachments/assets/cd37f596-ec10-4a1e-991b-5c130a9a8419)



