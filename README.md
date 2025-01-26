
![Plane](https://honeywell.scene7.com/is/image/honeywell/AeroBT-s_414384259_Business-Jet_2880x1440)
# Getting Into Flight
Analysis by Jordan Scriven  

## Business Understanding
Expanding into a new industry, like flight, is exciting!  With the proper research, we can run a safe and profitable aviation division that will take our company to new heights.

## Data Understanding
The National Transportation Safety Board collected aviation accident data from 1948 to 2022.  This data not only provides information on the flight, such as the plane and weather conditions, but also on the acccident itself with records on injuries and the condition of the plane post-accident. With 60+ years of descriptive information at our hands, we need to determine which airplanes are going to give us the best chance at accomplishing our goal of expanding our business.

Because this data concentrates on the accidents and ignores successful flights, we will focus our attention on determining how to keep the outcome of the accidents to a minimum, meaning little to no injuries and minor aircraft damage.

### Data Preparation
Of the rows of data, we wanted to look only at those accidents or incidents regarding airplanes.  About 31% of the recorded data has an aircraft category listed, bringing our total incidents to analyze to just over 27,600.

## Exploratory Data Anlysis
The data includes information on the make and model of the planes.  There are many different makes, but the top 5 companies (Cessna, Piper, Beech, Boring and Mooney) total about 61% of the data, so we will concentrate on those 5 and compare the outcome of the accidents for each company.

![Severity of Injuries Per Airplane Make Chart](https://github.com/user-attachments/assets/667b92d2-d76b-483c-bb01-6fcedf1797c6)

![Severity of Damage Per Airplane Make Chart](https://github.com/user-attachments/assets/05212806-4d52-453e-b61a-c26a712ba539)

We also compared the outcome of accidents by engine type to see if the severity of injuries and aircraft damage is affected by the engine type.  While there are a few different engine types listed, a significant majority were either reciprocating or turbo engines, so we compared their outcomes.

![Severity of Injuries Per Engine Type Chart](https://github.com/user-attachments/assets/e6f3b578-793a-4ab7-a714-6fa1ace89785)

![Severity of Damage Per Engine Type Chart](https://github.com/user-attachments/assets/3197b40c-a3f2-4233-89b5-ef4fffd05a09)

Finally, we analyzed the effect of oustide factor of weather on the accidents.  We investigated the time of year of the accidents and the state of visibility the planes were flying through at the time of the crash. 

![Accidents Per Month](https://github.com/user-attachments/assets/9c45b6da-3df2-4f2d-bd3e-f9fcde396f79)

![Meterological Conditions](https://github.com/user-attachments/assets/e88e0dc8-73af-4019-a3b5-ea344606f12b)

## Conclusion

With the opening of this new aviation division of our company, we have two goals. 1. Keep our great reputation as a company who cares for their customers and 2. Make a profit.  In order to reach both those goals, we need to keep our people safe and minimize any damage to our aircrafts.

This analysis leads to recommendations for success.  With the data that we have in hand to analyze, we have come to the following conclusions:

*   **Utilize planes with turbo engines** In accidents involving airplanes with reciprocating engines, nearly 40% of the passengers were injured, including 17% fatalities.  On the other hand, of the passengers who were in accidents while flying on an airplane with a turbo engine, only 5% were injured and 2.5% were killed.  Additionally, turbo engines are more likely have an accident with only minor damage to the airline
*   **Stay grounded when the weather is bad** When the pilots are able to see with their own eyes rather than relying on instruments to guide them, crashes are less likely to end in fatalities.  Almost 20% of passengers involved in a crash while the instruments were guiding the plane had fatal injuries.
*   **Fly Boeing**  For the safety of our passengers, Boeing is the favorite.  Of the nearly 97,000 passengers recorded to be involved in an accident on a Boeing aircraft, 94% of them were entirely unharmed.  The next best Make of airplane in terms of uninjured passengers in accidents is Cessna with just 63% arriving unscathed.  Boeing also has the greatest likelihood of minimal damage to the aircraft as the result of an accident.  47% of the Boeing aircrafts incured minimal damange, allowing the company to refrain from substantial repair costs.
  
### Limitations
For the entirety of this analysis, we have made one big assumption.  We assume that all airplanes have equal probabilities of being involved in accidents.  Our data only contained accident information and nothing on successful flights.  Therefore, our conclusions were based on the plan to keep the harm, both to passengers and the aircraft, to a minimum.

### Recommendations

### Next Steps
