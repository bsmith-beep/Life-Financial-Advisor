# Life-Financial-Advisor
CS32 Final Project

# Discription of project,
A personalized financial expenses report based on sample questions the user responds to. The advisor takes into account the user's living situation, dependants, and location in order to generate a minimum income needed to live the inputted lifestyle, along with a second income that would allow for a more comfortable situation. The goal of the project is to give users a realistic sense of how their lifestyle choices impact their financial needs.

# Instructions,
Our code is easy to run. Simply run the FP Final file and answer the questions when prompted. The program will guide the user through a series of inputs, and any invalid answers will prompt acceptable responses so the program can continue running smoothly. At the end, the user is given a full breakdown of their monthly costs, yearly income estimates, and some personalized advice based on their choices.

# Outside contributers 
We used the Pset 3 rochambo code "if choice not in rps:" as a basis for ensuring that all our imputed answers are ones we are perpared for and our code knows how to respond to. 
Inorder to make sure our data was realworld applicable we gathered it from FAFH.gov and The World Population Review.
AI was used in debugging roles, where we imputed error codes and asked for help with errors. It was also used in cleaning up code when we combined different sections we had each written. In this case AI flaged duplicate methods and restructuring code, this was then reviewed by us to make sure nothing was lost and that the structure made sense. 

# Model Assumptions
This project uses a simplified financial model to estimate the yearly income needed for a user's future lifestyle. Because real-life costs vary by city, family situation, inflation, personal habits, and income level, the model relies on realistic averages rather than exact values. Housing costs are based on estimated median home prices by state and are adjusted depending on whether the user selects a house, condo, apartment, or mobile home. The monthly housing estimate is calculated as a percentage of that adjusted price to approximate rent or mortgage payments.

Food costs are estimated per adult and per child, with additional costs added depending on how often the user eats out each week. 
Transportation costs vary depending on whether the user selects a car, public transportation, biking, or walking, with car ownership being the most expensive based on national averages. 
Each child adds a fixed monthly cost to account for childcare, schooling, and other expenses, while utilities increase slightly with larger households.

Health, phone, internet, clothing, and personal care costs are all modeled using monthly estimates that scale depending on the household's size. Taxes are estimated as a flat percentage of total monthly expenses to give a more realistic pre-income requirement, and an additional percentage is added for savings or an emergency fund. While these numbers are grounded in real world data, they are simplified and meant to provide an estimate not and exact amount for financial advice.
