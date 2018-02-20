# Project 2: Open Data App - an RShiny app development project

![screenshot](rent-2.jpg)

## Room Hunt
Term: Spring 2018

+ Team #6
+ **Projec title**: + Team members
	+ Yuexuan Huang (Presenter)
	+ Wenyuan Gu
	+ Anshuma Chandak
	+ Zhongxing Xue
	+ Weibo Zhang

+ **Project summary**: 

People have described Apartment Hunting as a fate worse than Death. Do you remember your days when you were back in your home-country anxiously looking for an apartment that is affordable and safe? Inspired by every student's problem, we made an application that will help a renter find a room based on top two priorities- price and safety. Our application will provide a comprehensive view of the rent prices and crime rate in every street in the Manhattan Borough of New York City. 

The application is divided into three sections- a query map where the user can feed in their choices, and get all the apartment options categorized by crime rate and apartment price in their desired area. We have included information about the nearest police station, and subway. In the second section, we show the distribution of crime in Manhattan categorized by 3 crimes- Felony, Misdemeanor, and Violation. In the last section, we summarize our study by providing several insightful charts about the categories of crimes committed, and rent prices. 
We have used NYPD Complaint Data (to get crime related data), and Manhattan Housing Data from www.data.gov . 

Crimes receive different classifications according to their severity. The mildest crimes are known as violations, more serious crimes are known as misdemeanors, and the most serious crimes are known as felonies.A violation, sometimes called a petty offense, is the violation of an administrative regulation, an ordinance, a municipal code, and, in some jurisdictions, a state or local traffic rule. Misdemeanors are those crimes punishable by imprisonment for a year or lesser.Felonies are generally punishable by a fine, imprisonment for more than a year, or both. At common law, felonies were crimes that typically involved moral turpitude, or offenses that violated the moral standards of the community.

![screenshot](/app/Demo-for-Query-Map/app/www/total pie.png)

The above plot shows that Misdemeanor have the highest number of cases, followed by Felony and Violations. 


![screenshot](/app/Demo-for-Query-Map/app/www/mis pie.png)

Under Misdemeanor, we observe that assaults constitute the highest share of crimes followed by criminal mischief and drug related crimes. 

![screenshot](/app/Demo-for-Query-Map/app/www/scatterplot2.png)

The above plot shows the relationship between crime frequency and the rent. WE notice that areas with high rent prices have a lower incidence of crime. However, Chelsea and Clinton area seem to be an abnormality as both the rent prices and crime frequency are high. 

We also observe that crime in Manhattan is fairly evenly distributed with higher incidence of crime in Midtown area (towards the West Side), and Uptown Area. 



+ **Contribution statement**: ([default](doc/a_note_on_contributions.md)) All team members contributed equally in all stages of this project. All team members approve our work presented in this GitHub repository including this contributions statement. 

Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── app/
├── lib/
├── data/
├── doc/
└── output/
```

Please see each subfolder for a README file.

