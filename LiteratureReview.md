The Lit Review can take a few directions. For instance 
## What has been done so far with this dataset
* There are a few kernels available through Kaggle, but most of these kernels/notebooks were created three years ago. 
* BillurEngin's kernel (https://www.kaggle.com/bengin/mastering-the-sf-library-data) explores the factors contributing to library activity (# of checkouts, # of renewals). Her work is most similar to the objective of this project. However, it is noted that she used total checkouts as is and does not address that the number is cumulative. Therefore, patrons who registered in 2003 is likely to have a higher checkout counts, comparing to more recent users (say, those who registered in 2014 and 2015). 
* Sebastian Mantey's kernel (https://www.kaggle.com/bengin/mastering-the-sf-library-data) includes number of branch openings/reopenings from 2004 to 2016 from outside source. He tried to study the relationship between active users/non-active users and the number of users registered. Mantey may have ignored the fact that the data available here is total checkouts. Without looking at the average annual checkouts (calculated as total checkouts /2016-year registered) and simply using total checkouts to categorize active/non-active users, this will fairly penalize those who obtained their accounts as recent years. 


## What do we know about SFPL? 
* A crucial element, in addition to mathematics and programming skills, is domain knowledge. In particular, when working with this dataset,  it is important to have background information about the organization, San Francisco Public Library (SFPL). 
## What do we know about driving forces behind library activities? 
* Here, defined as number of checkouts and may number of renewals
* Ideally, we can find literature about studies done in the area of public libraries. If there is none, a broader scope (which covers all kind of libraries) will be used. 
