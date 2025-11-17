# MIST4610 Project 2
## Team name and Members
Group 6:
1) Aubrey Katzenmiller, [@aubreyk308](https://github.com/aubreyk308) 811343956
2) Akash Kodali, [@ank1234538](https://github.com/ank1234538) 811039006
3) Josh Tesar, [@joshtesar04](https://github.com/joshtesar04) 811846823
## Data Description
The dataset used in this project was obtained from NYC Open Data and is titled Motor Vehicle Collisions. It is maintained by the City of New York and updated daily to reflect every reported crash across all five boroughs. Each entry represents a single motor vehicle collision and includes detailed information such as the date and time of the crash, exact geographic coordinates, vehicle type or make, and contributing factors such as distracted driving or failure to yield. The dataset also records the number of people injured or killed in the incident, which allows us to analyze collision severity and identify patterns related to safety and risk throughout New York City.
## Question Desciption and Purpose
Research Question 1:
What are the most common causes of motor vehicle collisions in New York City?

Why we chose this question:
Understanding the leading causes of motor car collisions is vital for improving public safety and increasing the amount of prevented crashes. Identifying which factors like distracted driving, failure to yield, or speeding can contribute more to accidents helps guide policy decisions, traffic enforcement priorities, and public awareness. This has social importance (protecting pedestrians, cyclists, and drivers), economic implications (reducing costs from property damage and medical expenses), and public planning value (supporting data-driven street design decisions).
This ties into the dataset through a variable titled “Contributing Factor,” which lists the cause of the crash for each vehicle involved. By analyzing the frequency of these factors, we can determine the most common causes of collisions across the city.

Research Question 2:
How do fatality rates vary based on different conditions, such as time of day and location within New York City?

Why we chose this question:
This question matters because it examines when and where collisions are most severe, not just how often they happen. Analyzing this data allows for the city to figure out what factors are the most dangerous and provide corrective action. They can increase the safety of the city and focus efforts in the correct spots to lower the fatality rate of collisions in the city. The findings can influence public safety initiatives, emergency response planning, and transportation policy.The dataset contains variables for crash time, borough, geographic coordinates, and the number of persons injured or killed. By comparing these fields, we can identify patterns in fatal collisions based on both time and location.

## Modifications to the Data

Only minor data preparation was needed for our analysis. We filtered out rows with missing values in key fields such as crash time, location, and contributing factor so that our results were based on complete records. We then grouped the remaining data by categories such as time of day and borough, and created simple summaries and counts to identify trends. No major modifications were made to the dataset; we only organized and cleaned it to make the analysis clearer.
## Data Analysis and Results

QUESTION 1: What are the most common causes of motor vehicle collisions in New York City?


<img width="929" height="412" alt="image" src="https://github.com/user-attachments/assets/cb1424ab-a833-4453-acc1-29cb83752e70" />
<img width="929" height="412" alt="PNG image" src="https://github.com/user-attachments/assets/a7335e1d-7ee1-4df9-bd9c-81258cdecd58" />

When looking at the chart, we are able to see that most NYC collisions are caused by driver inattention, which appears far more often than any other factor in the dataset. There is also a large number of “Unspecified” entries, which suggests that many reports lack clear cause information, limiting the accuracy of analysis. Other common causes include things like following too closely or failing to yield, which help reflect typical issues in the cities dense traffic environment. Overall, the data implies that reducing distracted driving and improving reporting quality would have the biggest impact on lowering collisions.

<img width="929" height="412" alt="image" src="https://github.com/user-attachments/assets/08ad4f35-68e3-4b55-bbc5-65cbc99b208a" />
<img width="929" height="412" alt="PNG image" src="https://github.com/user-attachments/assets/67373c61-b29f-4ced-a1c2-859713a8c266" />

The visualization shows which vehicle types are most frequently involved in NYC collisions, with sedans and pickup trucks standing out compared to bikes, buses, and box trucks. This pattern makes sense given that sedans and pickups make up a large share of vehicles on NYC roads. Bikes and buses show far fewer collisions, likely because they operate in more regulated or protected traffic spaces. Overall, the data suggests that safety interventions aimed at passenger vehicles would have the greatest impact on reducing total crashes.



