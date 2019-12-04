# Clustering


K mean clustering

Introduction

The project to map out and analyse data collected from South East of England. The analysis in this project based on families, peoples categorised into three age groups, ten crime related variables, lifestyles, socio economic factors, education qualification levels, professions divided into seven groups and eight variables corresponds to type of land and building. A household described in the data as a person living alone or with a group of people living at the same address who share cooking facilities and share a living room or dining room. All 16plus in household is defined as an adult married, cohabiting couple with or without children (no information given about children) or alone parent with or without child. The project highlighted which districts are subject to crime or any particular crime through factor analysis and presented the result by carried out cluster analysis.

Data Exploration and Standardisation

The total Lands in the South East dataset are divided into eight parts in Domestic Building, Non-Domestics Building, Roads, Paths, Rail, Domestic Garden, Greenspace and Water. Some of variables like Rail, Path are covers in very small area of square metres as compare to Land covered by the Greenspace through its agriculture land and parks. In dealing with variable of small area will provide an estimate at smaller level and not be reliable estimate in working with larger area variable. This need to be standardised to represent a true value as a whole.

Variables for crime and hypothesis test


All ten variables records on crime are standardised. Visualisation of boxplot gives a vague picture in suggesting normality and only indicating a case of normality for these two variables - Other Theft Offences (Tht), Violence against the person (Vp).

Boxplot gives a quite mixture of picture of crime in the south east England. Reading, Slough and Hastings has outlier indicating higher variation of Robbery while Oxford and Crawley has Theft related offences. Isle of Wight is only district have outlier suggesting proportion of Drug related offences. Wokingham, South Bucks, Hart, Dartford, Tandridge and Mid Sussex are district have higher Fraud and Forgery than any other district in the South East. The outer outliers in other offences are in Lewes, Hastings, Crawley and Reigate & Banstead. The Isle of Wight has quite lower offences against vehicle while Slough, South Bucks and Windsor & maidenhead has higher proportion as compare to other districts of South East England. South Bucks has lower variation while Rushmoor has higher in Sexual offences.


Association between crime and certain type of building

The data shows there are strong relationship between certain type of property and crime.


Principal Component Analysis on crime 

Removing the variable which are non-contributory and have less impact by analysing the correlation matrix . The variables other theft offences, violence against person, road, path, domestic garden and other offences are remove in the date frame as it has less impact and perform pca.. After removing these six variable and investigate the correlation amongst all seven variable and find Greenspace  is not impact on other variable seven variables and removed for further analysis.

To determine number of factors in screeplot , look at line when it drop to horizontal and almost parallel  or  find the ‘elbow’ is another technical term used . The screeplot suggests maximum of three factors retain for factor analysis. Cumulative proportion also suggests three factors for analysis by measuring cumulative proportion of 90%.

Using Principal Component analysis techniques allows investigate maximum variance extracted these seven variables which are linear combinations of measured variable that retain as much information as possible from the original scores.

K mean Cluster analysis 

To analyse which of these district are similar or related to each other and this could be explain through  K mean Cluster analysis. 

To see which district fall under in a cluster is to plot Dendrogram and divide the whole into four parts (Cut tree into four cluster).


Reading, Slough, Brighton & Hove, Portsmouth, Southampton, Eastbourne, Hastings, Gosport, Rushmoor, Oxford, Crawley, Worthing are 12 districts which are in Cluster 1.

In Cluster 2 , Medway, Bracknell Forest, Milton Keynes, Aylesbury Vale ,Wycombe ,Basingstoke & Deane, Eastleigh, Fareham, Havant, Winchester, Dartford,  Maidstone, Thanet, Tunbridge Wells, Cherwell, Epsom & Ewell, Guildford, Mole Valley, Reigate & Banstead ,Spelthorne ,Woking , Chichester  are in the cluster 3 consists of  22 districts.

Isle of Wight, Lewes, Rother, Wealden, East Hampshire, Hart, New Forest, Test Valley, Ashford, Canterbury, Dover, Gravesham, Shepway, Swale, Tonbridge and Malling ,South Oxfordshire, Vale of White Horse, West Oxfordshire, Surrey Heath, Tandridge, Adur, Arun, Horsham  and Mid Sussex are the largest cluster in group 3 which has  24 districts .

West Berkshire, Windsor and Maidenhead, Wokingham, Chiltern, South Bucks, Sevenoaks, Elmbridge, Runnymede and Waverley are of 9 districts in the smallest cluster.
