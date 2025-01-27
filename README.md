
![Plane](https://honeywell.scene7.com/is/image/honeywell/AeroBT-s_414384259_Business-Jet_2880x1440)
# Getting Into Flight
Analysis by Jordan Scriven  

## Business Understanding
Expanding into a new industry, like flight, is exciting!  With the proper research, we can run a safe and profitable aviation division that will take our company to new heights.

## Data Understanding
The National Transportation Safety Board collected aviation accident data from 1948 to 2022.  This data not only provides information on the flight, such as the plane and weather conditions, but also on the acccident itself with records on injuries and the condition of the plane post-accident. With 60+ years of descriptive information at our hands, we need to determine which airplanes are going to give us the best chance at accomplishing our goal of expanding our business.

Because this data concentrates on the accidents and ignores successful flights, we will focus our attention on determining how to keep the outcome of the accidents to a minimum, meaning little to no injuries and minor aircraft damage.

### Data Preparation
Of the rows of data, we wanted to look only at those accidents or incidents regarding airplanes.  About 70% of the recorded data has invovled an airplane, bringing our total incidents to analyze to just over 62,500.

To make the data easier to handle, we dropped unnecessary columns, replaced blanks with "unknowns" and added some columns that would be helpful.

## Exploratory Data Anlysis
The data includes information on the make and model of the planes.  There are many different makes, but the top 5 companies (Cessna, Piper, Beech, Boring and Mooney) total about 83% of the data, so we will concentrate on those 5 and compare the outcome of the accidents for each company.

![Severity of Injuries Per Airplane Make Chart](https://github.com/user-attachments/assets/f9c6d8c8-3266-4080-a3a8-2aa0ce9f7017)

![Severity of Damage Per Airplane Make Chart](https://github.com/user-attachments/assets/49d3a7bb-7153-4654-ae8b-bc4fdcc26298)

We also compared the outcome of accidents by engine type to see if the severity of injuries and aircraft damage is affected by the engine type.  While there are a few different engine types listed, a significant majority were either reciprocating or turbo engines, so we compared their outcomes.

![Severity of Injuries Per Engine Type Chart](https://github.com/user-attachments/assets/4ca70990-2b51-4ed6-8eac-c71d33228905)

![Severity of Damage Per Engine Type](https://github.com/user-attachments/assets/a4528243-871c-4e1a-8ade-277c2f5fdeab)

Finally, we analyzed the effect of oustide factor of weather on the accidents.  We investigated the time of year of the accidents and the state of visibility the planes were flying through at the time of the crash. 

![Accidents Per Month](https://github.com/user-attachments/assets/93c69a55-7586-4b5f-9235-fa8927733bf4)

![Meterological Conditions](https://github.com/user-attachments/assets/59cf5d30-6566-47d1-a8e5-43ba27f8a5c5)

## Conclusion

With the opening of this new aviation division of our company, we have two goals. 1. Keep our great reputation as a company who cares for their customers and 2. Make a profit.  In order to reach both those goals, we need to keep our people safe and minimize any damage to our aircrafts.

This analysis leads to recommendations for success.  With the data that we have in hand to analyze, we have come to the following conclusions:

*   **Utilize planes with turbo engines** In accidents involving airplanes with reciprocating engines, nearly 41% of the passengers were injured, including 18% fatalities.  On the other hand, of the passengers who were in accidents while flying on an airplane with a turbo engine, less than 5% were injured and 2.5% were killed.  Additionally, turbo engines are more likely have an accident with only minor damage to the airline
*   **Stay grounded when the weather is bad** When the pilots are able to see with their own eyes rather than relying on instruments to guide them, crashes are less likely to end in fatalities.  Over 23% of passengers involved in a crash while the instruments were guiding the plane had fatal injuries.
*   **Fly Boeing**  For the safety of our passengers, Boeing is the favorite.  Of the nearly 225,000 passengers recorded to be involved in an accident on a Boeing aircraft, 94% of them were entirely unharmed.  The next best Make of airplane in terms of uninjured passengers in accidents is Cessna with just 62% arriving unscathed.  Boeing also has the greatest likelihood of minimal damage to the aircraft as the result of an accident.  43% of the Boeing aircrafts incured minimal damange, allowing the company to refrain from substantial repair costs.
  
### Limitations
For the entirety of this analysis, we have made one big assumption.  We assume that all airplanes have equal probabilities of being involved in accidents.  Our data only contained accident information and nothing on successful flights.  Therefore, our conclusions were based on the plan to keep the harm, both to passengers and the aircraft, to a minimum.

### Next Steps
Further analysis could help us develop the aviation division of our company even more:

*   **Add data regarding successful flights** With additional information on all flights, including those that are successful, we could analyze which planes are not only more likely to result in minimal injury and damage when an accidents occurs but also recommend planes that are less likely to be involved in an iccident at all.
*   **Model Cost Information** In order earn a profit in the aviation division, modeling the cost of each flight and the income resulting from each flight would be beneficial.

