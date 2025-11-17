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


<img width="700" height="310" alt="image" src="https://github.com/user-attachments/assets/cb1424ab-a833-4453-acc1-29cb83752e70" />
<img width="700" height="310" alt="PNG image" src="https://github.com/user-attachments/assets/a7335e1d-7ee1-4df9-bd9c-81258cdecd58" />

When looking at the chart, we are able to see that most NYC collisions are caused by driver inattention, which appears far more often than any other factor in the dataset. There is also a large number of “Unspecified” entries, which suggests that many reports lack clear cause information, limiting the accuracy of analysis. Other common causes include things like following too closely or failing to yield, which help reflect typical issues in the cities dense traffic environment. Overall, the data implies that reducing distracted driving and improving reporting quality would have the biggest impact on lowering collisions.

<img width="700" height="310" alt="image" src="https://github.com/user-attachments/assets/08ad4f35-68e3-4b55-bbc5-65cbc99b208a" />
<img width="700" height="310" alt="PNG image" src="https://github.com/user-attachments/assets/67373c61-b29f-4ced-a1c2-859713a8c266" />

The visualization shows which vehicle types are most frequently involved in NYC collisions, with sedans and pickup trucks standing out compared to bikes, buses, and box trucks. This pattern makes sense given that sedans and pickups make up a large share of vehicles on NYC roads. Bikes and buses show far fewer collisions, likely because they operate in more regulated or protected traffic spaces. Overall, the data suggests that safety interventions aimed at passenger vehicles would have the greatest impact on reducing total crashes.

<img width="700" height="310" alt="PNG image" src="https://github.com/user-attachments/assets/8f769d1c-8f1c-44b7-8ea2-26e9623d0d40" />
<img width="700" height="310" alt="PNG image" src="https://github.com/user-attachments/assets/9ad9b7c9-a61b-4799-8acd-795afef5d8b2" />

This metric shows the total number of reported vehicle collisions in NYC, which exceeds 1,048,000 incidents in the dataset. This high number reflects how frequent crashes are in a dense, high traffic city with heavy pedestrian, bike, and vehicle activity. It provides important context for the rest of the dashboard by showing the overall scale of the problem. The total collision count highlights the need for strong citywide safety measures and the importance of consistent data reporting.

<img width="700" height="310" alt="PNG image" src="https://github.com/user-attachments/assets/23bd495c-3474-46ef-a301-c590f7eca1d9" />
<img width="700" height="310" alt="PNG image" src="https://github.com/user-attachments/assets/224533b9-edae-415b-a3a1-41c98cc26848" />

Brooklyn and Queens report the highest number of collisions, which fits their large populations and heavy traffic volumes. Manhattan also shows a high count, likely due to dense intersections and constant commercial activity. The Bronx falls in the middle, while Staten Island has the fewest collisions, reflecting its lower density and slower traffic flow. Overall, the data helps show a clear relationship between borough size, traffic intensity, and total collisions.

<img width="700" height="310" alt="PNG image" src="https://github.com/user-attachments/assets/a756bfbf-81b2-41b4-a352-8e0a5d333561" />
<img width="700" height="310" alt="PNG image" src="https://github.com/user-attachments/assets/36b70294-d922-4ef1-b79f-f233b713a8f0" />

Collisions in NYC peak on Fridays, with Thursday and Tuesday close behind. Weekdays in general have more crashes than weekends, likely due to heavier commuting traffic and more cars on the road. Saturday shows a moderate drop, and Sunday has the fewest collisions overall. This pattern suggests that weekday congestion and routine work travel contribute heavily to NYC crash volume.

Overall, the NYC collision data shows that crashes are heavily driven by human behavior, with driver inattention being the leading cause across the city. Collisions are most common in higher traffic situations, with more collisions happening in the busier days and boroughs. Sedans and other passenger vehicles account for most crashes, which fits the makeup of NYC’s vehicle population. With more than one million total reported collisions in the dataset, the scale of the issue is significant. Together, these trends suggest that reducing distracted driving, improving traffic flow, and targeting high population areas would have the greatest impact on improving safety.


QUESTION 2: How do fatality rates vary based on different conditions, such as time of day and location within New York City?

<img width="700" height="310" alt="PNG image" src="https://github.com/user-attachments/assets/b0c44a32-39f7-4f2a-aa84-8805449c6acd" />
<img width="700" height="310" alt="PNG image" src="https://github.com/user-attachments/assets/761d75f8-3ea9-4aab-b38a-be720dab157c" />

The scatter plot shows that most NYC collisions result in injuries, but that very few lead to fatalities, even when the number of injured people is high. Fatalities remain relatively rare events and cluster at low values even when injuries exceed 100+. Overall, this suggests that while severe crashes do occur, NYC’s fatality rate stays low compared to the overall volume of injury related collisions nationwide. This is likely due to the low speed driving styles in the city.

<img width="700" height="310" alt="PNG image" src="https://github.com/user-attachments/assets/0e07d017-5abe-4053-9dff-139932ebf947" />
<img width="700" height="310" alt="PNG image" src="https://github.com/user-attachments/assets/6b743d9b-47ac-4604-a209-6a2a015816c2" />

This metric shows the total number of people injured or killed in NYC collisions, which exceeds 391,000 victims in the dataset. The number highlights how widespread collisional harm is, even though fatalities themselves remain relatively rare. It provides important context for the rest of the analysis by showing the human impact behind the crash numbers. Each one of those victims, over 391,000, are people that were involved and injured in a crash in some way. Overall, the scale of injuries emphasizes the need for targeted safety measures, particularly in high risk areas and times of day.

<img width="700" height="310" alt="PNG image" src="https://github.com/user-attachments/assets/9f2c9333-cea1-48c2-a975-353544943912" />
<img width="700" height="310" alt="PNG image" src="https://github.com/user-attachments/assets/323d9e27-0a3e-4a42-8b03-6a9cac11660a" />

When looking at the data, we are able to see that SUVs and Sedans cause a majority of the motor vehicle fatalities in the city. Motorcycles also appear prominently, reflecting their higher vulnerability in collisions. Larger commercial vehicles like box trucks and buses contribute to fewer fatalities, likely because they are operated by trained drivers and have stricter regulations. Overall, the results suggest that passenger vehicles and motorcycles are involved in most fatal incidents, highlighting key areas for targeted safety interventions.

<img width="700" height="310" alt="PNG image" src="https://github.com/user-attachments/assets/f0c46c51-d651-428d-ab7b-b681cc4365fe" />
<img width="700" height="310" alt="PNG image" src="https://github.com/user-attachments/assets/fb5a49cd-98e8-49b0-be56-a772dd52fa3c" />

As can be seen above, fatal collisions are not evenly distributed across NYC ZIP codes, with some areas experiencing significantly more deaths than others. A few ZIP codes stand out with much higher fatality counts, which often corresponds to major roads, highway access points, or higher traffic neighborhoods. Other ZIP codes show much lower numbers, likely due to quieter residential streets and less vehicle volume. Overall, this highlights how location plays a major role in fatal crash risk and suggests that certain ZIP codes may need targeted safety measures or enforcement.

<img width="700" height="310" alt="PNG image" src="https://github.com/user-attachments/assets/c53ac3dd-c3bd-4e34-96f1-70d7a137d112" />
<img width="700" height="310" alt="PNG image" src="https://github.com/user-attachments/assets/05275d54-712a-4264-bffc-a4c4cad6ae1b" />

The chart above helps show that pedestrians and motorists make up the majority of traffic fatalities in NYC, with pedestrians slightly higher overall. Cyclist deaths are much lower in comparison, but still represent a significant safety concern given NYC’s growing bike usage. The high pedestrian fatality count reflects the city’s dense streets, heavy foot traffic, and frequent pedestrian and vehicle interactions. Overall, the data highlights pedestrians and motorists as the most at risk groups, suggesting these areas need the strongest safety interventions.

Overall, the fatality data shows that traffic deaths in NYC vary widely depending on location, vehicle type, and who is involved in the crash. Fatalities cluster heavily in certain ZIP codes and along major traffic corridors, indicating that some neighborhoods face much higher risk than others. Sedans, SUVs, and motorcycles appear most often in fatal crashes, while pedestrians and motorists make up the largest share of victims. Even though injuries are common, fatalities remain relatively rare and usually occur in the most severe or higher speed incidents. Altogether, the patterns suggest that targeted safety measures in higher risk areas and for vulnerable road users could significantly reduce fatal outcomes.


