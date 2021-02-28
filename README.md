# Yi_Analytics-Portfolio
My Marketing Analytics Works

## Project1: Revitalize Product Set
* (Conjoint Analysis; Cluster Analysis; Competitive Analysis; Cannibalization; Pricing Policy)

### CASE BACKGROUND:
*EarlyRiders, our client, had a recent management change and realized that their product set was underperforming. They currently offer two products and one in particular was not doing well. The management team decided after much deliberation to revitalize their product portfolio based on the opinions of potential end-users.*

For this purpose, we ran a conjoint analysis based on 200 individuals, these individuals are made up of parents of 2-4 year old kids who planned to purchase a toy horse. And we were in charge of analyzing the data and creating a presentation to give to the management team of EarlyRiders.

Here is the project presentation slides. [Click Here](https://github.com/huangyianna/Yi-Analytics_Portfolio/blob/main/ToyHorsePPT.pdf)

### Analytics Design
Decision: Which product line based on long term profitability

Decision Criteria:

* Expect profit (Completely New or Adjust Current) v.s. Current product line (Expected)
* Clustering Output (Segmentations)
* Market share simulation
* Scenario, Possibility of Product Line, Influenced by clustering

### Attributes
* From Survey: Gender, Age
* From Products: Size, Motion, Style, Price

### Priori Segment by “Age”

summary (lm(ratings~priceage+sizeage+motionage+styleage, data=prioridf))

![image](https://user-images.githubusercontent.com/64434266/109405460-ac43f480-793e-11eb-98b3-3dab8b715f5a.png)

### Priori Segment by “Gender”
summary (lm(ratings~pricegender+sizegender+motiongender+stylegender,data=prioridf))

### Post Hoc: Cluster Modeling

3 segments supported by average silhouette Total within sum of square–visual intuition
![image](https://user-images.githubusercontent.com/64434266/109405497-1e1c3e00-793f-11eb-8b96-362d2cd2761a.png)

### R Code
[Click here to see the code](https://www.dropbox.com/s/k5ka7nib7spv7e0/ToyHorsePPT.pdf?dl=0)




