# Mobile_Usage_Analysis:

Report Link : https://1drv.ms/u/c/97ecacf04094eef0/EeoLGIqsKpVJqUe9E4MfbYABv0kZHKzhe7_kos9n0oTZaA?e=iVzmf7

## Problem Statement

This report gives information overall the user's mobile usage through different ratings.
this report gives information about mobile usage in criteria of gender and age group also.

### Steps Followed

- Step-1 : Clean and transform data to understanding the insights in dataset and give the proper format like "Tabular format".
- Step-2 : Load data into power BI desktop as Xlsx file.
- Step-3 : After load data create some calculated column as per requirement the calculated columns are user_behaviour_class, Age_group.
- Step-4 : For creating new column following Dax expression was written;

 Behaviour_class= 
		 if([age]<=2)="Low"
		 if([age]<=4)="Medium"
		 Else="High"

Age_Group=
		if([age]<20)="Below 20"
		if[age]<=30)="20-30"
		if([age]<=40)="30-40"
		if([age]<=50)="40-50"
		Else:"50-59"

Snap of new calculated column :

![Image](https://github.com/user-attachments/assets/f01077d6-c5ae-4152-b6a1-a12010d7afd3)

- Step-5 : Calculated the count of user,

	count of user = count(user id)

A card visual was used to represent the count of user

Snap of visual:

![Image](https://github.com/user-attachments/assets/8c417e2a-473e-4b41-ae2e-2559b0e2c987)

- Step-6 : Calculated avg of user,

	Avg of user=avg(user id)

A card visual was used to represent the avg of user 

Snap of visual:

![Image](https://github.com/user-attachments/assets/f2ef57f0-3091-439c-a5cf-7c02b94d7b4c)

- Step-7 : Calculated avg of data using,

	Avg of user=avg(data usage)

A card visual was used to represent the avg of data usage 

Snap of visual:

![Image](https://github.com/user-attachments/assets/95be6f44-1f3c-4b4e-9043-e78428172061)

After  all that things the snap of report is :

![Image](https://github.com/user-attachments/assets/efa97d9e-8c49-4f26-805f-6991d2da5247)

# Insights

Following some information's are drawn from report; 

Number of user (Male): 364 (52%)

Number of user (Female) = 336 (48%)

Number of user (Android) = 554 (79%)

Number of user (IOS) = 146 (21%)

## Rating as per age_group;

Age below-20 = 29

Age between "20-29" = 180

Age between "30-39" = 164

Age between "40-49" = 159

Age between "50-59" = 174

### Avg_Age of users:

Avg age of users (Female) = 38

Avg age of users (Male) = 39

		
































	
