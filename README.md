#Magento 1.x MageWorkshop Detailed Review extension localization

##How to localize?

Copy CSV file(s) from en_US directory to the appropriate local, eg fr_FR related to the French - France. And make a translation line by line.
eg Let's take a string from file MageWorkshop_DetailedReview.csv 

> "Review Text","Review Text"

and translate it to the french, should be something like below
 
>"Review Text","Réviser le texte"

Put localization directory with files to the appropriate directory of Magento by the path {project_root}app/locale/.