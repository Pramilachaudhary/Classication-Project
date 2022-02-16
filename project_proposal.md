# Project Proposal of Classification project

## Question:
Building a classification model for A Food Science Lab, which tests food items to determine their physical and chemical characteristics
to get some useful information for their research. They are interested to knowing whether a mushroom is edible or poisonous for their
research on developing medicinal properties out of poisonous mushrooms which treat different kinds of diseases. 
A classification model will predict if the mushroom is poisonous or not using different features like cap shape, gill color, odor, seasons etc. 


## Assumptions:
The Assumption made here is that the poisonous mushroom has medicinal properties in them and edible mushroom dont.

## Dataset:

https://archive.ics.uci.edu/ml/datasets/Secondary+Mushroom+Dataset

**Data Description:

One binary class divided in edible=e and poisonous=p (with the latter one also containing mushrooms of unknown edibility). 
Twenty remaining variables (n: nominal, m: metrical) 
1. cap-diameter (m): float number in cm 
2. cap-shape (n): bell=b, conical=c, convex=x, flat=f, sunken=s, spherical=p, others=o 
3. cap-surface (n): fibrous=i, grooves=g, scaly=y, smooth=s, shiny=h, leathery=l, silky=k, sticky=t, wrinkled=w, fleshy=e 
4. cap-color (n): brown=n, buff=b, gray=g, green=r, pink=p,purple=u, red=e, white=w, yellow=y, blue=l, orange=o, black=k 
5. does-bruise-bleed (n): bruises-or-bleeding=t,no=f 
6. gill-attachment (n): adnate=a, adnexed=x, decurrent=d, free=e, sinuate=s, pores=p, none=f, unknown=? 
7. gill-spacing (n): close=c, distant=d, none=f 
8. gill-color (n): see cap-color + none=f 
9. stem-height (m): float number in cm 
10. stem-width (m): float number in mm 
11. stem-root (n): bulbous=b, swollen=s, club=c, cup=u, equal=e, rhizomorphs=z, rooted=r 
12. stem-surface (n): see cap-surface + none=f 
13. stem-color (n): see cap-color + none=f 
14. veil-type (n): partial=p, universal=u 
15. veil-color (n): see cap-color + none=f 
16. has-ring (n): ring=t, none=f 
17. ring-type (n): cobwebby=c, evanescent=e, flaring=r, grooved=g, large=l, pendant=p, sheathing=s, zone=z, scaly=y, movable=m, none=f, unknown=? 
18. spore-print-color (n): see cap color 
19. habitat (n): grasses=g, leaves=l, meadows=m, paths=p, heaths=h, urban=u, waste=w, woods=d 
20. season (n): spring=s, summer=u, autumn=a, winter=w

## Tools:

Python Pandas and Numpy for data clean, data restructuring, exploratory data analysis and feature engineering
Tableau Public for exploratory data analysis and data visualization
Python Matplotlib, Seaborn for data visualization
Python Scikit-learn for classification models

## MVP Goal:

A baseline classification model.

