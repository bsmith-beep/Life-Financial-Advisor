# Life-Financial-Advisor
CS32 Final Project

# Discription of project,
A personalised financial expenses report based on sample questions the user responds to. The advisor takes into account the user's living situation, dependants and location inorder to generate a minimum income needed to live the imputed lifestyle and a second income that would allow for a more comefortable situation. 

# Instructions,
Our code is easy to run, simply run the FP Final file and answer the questions when prompted, invalid answers will prompt you with acceptable answers. 

# Outside contributers 
We used the Pset 3 rochambo code "if choice not in rps:" as a basis for ensuring that all our imputed answers are ones we are perpared for and our code knows how to respond to. 
Inorder to make sure our data was realworld applicable we gathered it from FAFH.gov and The World Population Review.
AI was used in debugging roles, where we imputed error codes and asked for help with errors. It was also used in cleaning up code when we combined different sections we had each written. In this case AI flaged duplicate methods and restructuring code, this was then reviewed by us to make sure nothing was lost and that the structure made sense. 



ASSUMPTIONS:
## Model Assumptions

This project uses a simplified financial model to estimate the yearly income needed for a user's future lifestyle. Because real-life costs vary by city, family situation, inflation, personal habits, and income level, the model uses realistic average estimates instead of exact predictions.

### Housing
Housing costs are based on estimated median home prices by state. The program then adjusts the cost based on housing type:
- House: 100% of the state baseline
- Condo: 85%
- Apartment: 60%
- Mobile home: 35%

The monthly housing estimate uses 0.6% of the adjusted home price. This is meant to approximate monthly rent or a mortgage-like housing payment.

### Food
Food costs are estimated at about $485 per adult per month and $300 per child per month. Eating out adds extra cost based on how many days per week the user says they eat out.

### Transportation
Car ownership is estimated at about $965 per month, based on AAA's 2025 estimate for the average monthly cost of owning and operating a vehicle. Public transportation, biking, and walking are estimated at lower monthly costs.

### Children
Each child adds about $1,200 per month. This represents a simplified estimate of childcare, school expenses, clothing, food, activities, and other child-related costs.

### Utilities
Utilities are estimated at $412 per month, based on average electric, gas, and water costs. Each child adds a small additional amount because larger households tend to use more utilities.

### Health
Health costs are estimated based on whether the user is single or married, with additional monthly cost added for each child. This is a simplified estimate of health insurance and medical expenses.

### Taxes
Taxes are estimated at 22% of monthly expenses. This is not an exact tax calculation, but it gives the user a more realistic idea of how much income they may need before taxes.

### Savings
The model adds 10% for savings or an emergency fund. This represents money that should be saved for emergencies, retirement, or future financial goals.

### Limitations
This model is not financial advice. It is an educational estimate. Actual costs can vary depending on city, income, lifestyle, inflation, insurance plans, debt, and personal choices.
