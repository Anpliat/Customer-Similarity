# Customer Similarity

**Purpose:** Assess the similarity between supermarket customers. 

### Purpose: *Assess the similarity between supermarket customers.* 

### Data
The dataset includes 10,000 supermarket customer profiles with the following attributes:
Attribute | Content
--- | ---
Customer ID | The unique id of the customer. 
Age | The age of the customer. 
Sex | Male-Female. 
Marital Status | Married, Single, Divorced. 
Education | Primary, Secondary, Tertiary. 
Annual Income | The annual customer income. 
Customer Rating | The rating of the supermarket from the customer (Poor, Fair, Good, Very Good, Excellent) 
Persons in Household | Number of persons in the household. 
Occupation | The occupation of each customer (retired, housemaid, unemployed, management, entrepreneur, blue-collar, self-employed, services, technician). 
Groceries | A list of the customer groceries. 

### Workflow for calculating customer similarity
To calculate the similarity between the customers, we used the following steps: 
1. Separate the attributes to nominal, numerical, ordinal and set 
2. Convert the object types to categorical 
3. Create the ordering categories per ordinal attribute 
4. Find the null/NA values in numerical attributes and replace them with the mean of the rest of the values 
5. Create dissimilarity matrices per attribute type 
6. Calculate the dissimilarity matrix for all given attributes 
