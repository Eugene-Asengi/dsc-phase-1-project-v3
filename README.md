# Aircraft Safety Survey.

![Image_Alt](https://github.com/Eugene-Asengi/dsc-phase-1-project-v3/blob/37bb9e320ec5354b2ea4f5b0f5740134b2bea66c/Aircraft%20photo.jpg)

Tableau link:- https://public.tableau.com/app/profile/eugene.asengi/viz/Phase1projectvisualizations/Dashboard1?publish=yes


# Introduction
The aircraft industry has many options such as; the dimensions, functionality, cost and safety. In this analysis, the point is to investigate on the safety and wellbeing of various aircrafts utilizing the accident data from the Aviation_Data.csv.

# Notebook Structure
Data collection

Data preprocessing

Exploratory data analysis(EDA)

Comparative analysis and Visualization

Conclusion and insights

# Business Questions with Respect to Safety
1. What are the best types of aircraft to invest in that are the least risky?
2. How to guarantee which engine type is the safest in an aircraft?
3. What backup plans are in place for flight systems?

# Business Understanding

**Problem statement** - Identifying the least risky aircraft to launch the company's new venture at a reasonable and fair price. Moreover, to achieve a successful entry into the market.
**Key Stakeholders** - Stakeholders will be of a wide range.
Internal {Company stakeholders, potential investors}; External {government policies, competition(other airline businesses), customers}
**Responsibility** - Acclimating to the aviation sector successfully and selecting an aircraft with the lowest risk.
**Resources**- Industry reports, budget, data on aircraft safety, and expert consultations.
**Risks** - Possibility of financial loss, accidents involving safety.

## Project Overview

My project targets to know the sorts of planes utilized in business/commercial and private enterprises. What place manufacturing and assembling companies are more inclined to accidents and mishaps. I expect to know whether the accidents are caused by human error or the plane's condition. The recurrence of accidents and losses in the business is significant. Therefore, I need to realize how frequently plane accidents occur.

### Data Understanding

My project entails information that has previously been collected by different data scientists. The data is stored in **Kaggle** whereby it is updated regularly and is stored in a **csv format**. When I read the data to my notebook using the pandas' library, I get a data frame with 90348 rows and 31 columns. From a brief look at the data frame, we realize that the information we are dealing with is from the investigation of aircraft accidents. I have both categorical and continuous data, with the former making the most of our data.

### Data Cleaning
- I have had to dig deeper after understanding the data to determine what is necessary/required and why. It is crucial to enter the market equipped with clear, extensive, comprehensive, and relevant knowledge. I identified the total number in percentage(%) of missing values in all columns whereby, it provided a basis for their relevance to provide key insights into my project. 
- Decided to drop columns that are not relevant to my study and they included: Schedule, FAR.Description, Latitude, Longitude, Location, Air.carrier and Airport.Name. The column named Schedule has more than 85% missing values and Air.Carrier has more than 80% missing values as well.
- Next, all rows with missing values were not adding any value to the data, hence I dropped them. Continuous data with null values were replaced by their **median** since it is less sensitive to outliers than mean.

VISUALIZATIONS.  

This is a visualization that portrays a comparison of Engine types that caused the highest number of fatal accidents.
![Image_Alt](https://github.com/Eugene-Asengi/dsc-phase-1-project-v3/blob/bb88df5e76a121244803204f511fdf90b952d7c8/VIZ1.png)  

This is a visualization that portrays a comparison of the type of Aircraft categories with minor injuries after accidents.
![Image_Alt](https://github.com/Eugene-Asengi/dsc-phase-1-project-v3/blob/4c8f5bc141d6a0e2f46b7d0824f3768ca319ea45/VIZ4.png)

## Conclusion and findings
Based on the comprehensive analysis and exploratory data analysis (EDA) conducted, the following conclusions can be drawn:  

1. Engine-type turbo fan caused most fatal accidents whereas geared turbo fan & LR were the most safest engines since they did not cause any accidents.  
2. Safest aircraft were; Blimp & Airplanes. Blimp has no fatalities at all and a low injury rate overall, whereas airplanes have low fatal injuries and the highest rate of uninjured individuals, hence they seem relatively safe.  
3. WSFT is the aircraft that recorded the least amount of survivors after an accident, therefore being considered the most dangerous aircraft.  
4. Powered-Lift, ULTR, and UNK are the aircraft that did not cause any fatal injuries after an accident.

## RECOMMENDATIONS
Based on our conclusions and observations, we can go ahead and make the following recommendation: The best engine types to be used in aircraft are Geared Turbofan and LR since they have they caused zero(0) fatal accidents. As the company decides to venture in this business they ought to invest in the two engines.

