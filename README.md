# Cancer Drugs Analysis
In this study, 250 mice were treated through a variety of drug regimes over the course of 45 days. Their physiological responses were then monitored over the course of that time. 
I used Python and Matplotlib to show how four treatments (Capomulin, Infubinol, Ketapril, and Placebo) compare.

## Results Observations
*   During the treatment period, only 2 drugs were effective in reducing tumor volume. As shown in the chart below, the drugs, Capomulin and Ramicane, managed to reduce tumor volume by 19.48% and 22.32% respectively. On the other hand, 3 drugs performed worse than the Placebo in terms of tumor volume reduction. Ketapril, Naftisol and Stelasyn showed the worst performances with a tumor size increase of 57.03%, 52.92% and 52.09% respectively.
 ![04_changes.png](/Pymaceuticals/Images/04_changes.png)
  
*   Considering survival rate, again, Capomulin and Ramicane achieved the best results, with over 90% of subjects surviving at the end of the treatment period. Although some drugs obtained results above Placebo in terms of tumor volume reduction, they did not perform well when analyzing the survival rate. Infubinol (34%) and Propriva (26%) achieved the two worst survival rates in the study, as shown in the chart below. Using only these two criteria, Survival Rate and Tumor Volume, one can assume that while they are more efficient than Placebo in reducing tumor volume, they can be very aggressive also to the subject's body.
![03_survival_rates.png](/Pymaceuticals/Images/03_survival_rates.png)

*   Regarding Metastatic spread during the treatment all but one drug performed better then the Placebo. The metastatic sites for the two most efficient drugs in the study, Capomulin and Ramicane, remained at levels below 1.5, again, indicating these drugs as a general good choice as cancer medicine.
![02_spread.png](/Pymaceuticals/Images/02_spread.png)

