# ML-Insurance-Competition


In the insurance business, applicants are assigned risk categories based on their past claim history and expected claim frequency/amounts for future. Claim frequency, severity and loss ratio are key factors used to assign risk categories to applicants


The aim of this competition is to develop models to predict these following metrics given the attributes of an applicant:

1.Target1 (Claim Incurred flag): If "Claim Count" >= 1 then 1 else 0

2.Target2 (Frequency): 1000*("Claim Count"/ "Gross Premium Excl PI")

3.Target3 (Loss Ratio): "Claim Incurred"/ "Gross Premium Excl PI"
