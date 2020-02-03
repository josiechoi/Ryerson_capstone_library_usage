The Lit Review can take a few directions. For instance 
## What has been done so far with this dataset
* There are a few kernels available through Kaggle, but most of these kernels/notebooks were created three years ago. 
* BillurEngin's kernel (https://www.kaggle.com/bengin/mastering-the-sf-library-data) explores the factors contributing to library activity (# of checkouts, # of renewals). Her work is most similar to the objective of this project. However, it is noted that she used total checkouts as is and does not address that the number is cumulative. Therefore, patrons who registered in 2003 is likely to have a higher checkout counts, comparing to more recent users (say, those who registered in 2014 and 2015). 
* Sebastian Mantey's kernel (https://www.kaggle.com/bengin/mastering-the-sf-library-data) includes number of branch openings/reopenings from 2004 to 2016 from outside source. He tried to study the relationship between active users/non-active users and the number of users registered. Mantey may have ignored the fact that the data available here is total checkouts. Without looking at the average annual checkouts (calculated as total checkouts /2016-year registered) and simply using total checkouts to categorize active/non-active users, this will fairly penalize those who obtained their accounts as recent years. Furthermore, Mantey's conclusion that "[b]ut a large part of that growth was either due to patrons who didn't use the service at all, or patrons who stopped using the service after a short time. And as a library official, that's probably not a development that you would like to see" did not take into consideration that the variety of services provided by public library. For instance, even if there is a drop in total checkouts in print materials, it can be well-compensated by an increase of usages in electronic resources. Also, data for patrons who use the facilities for library programmes, study space, meeting space, browsing collections is not included in this dataset. Therefore, it is inconclusive to say that SFPL grew from growth's sake simply based on this dataset. 


## What do we know about SFPL? 
* A crucial element for data science, in addition to mathematics and programming skills, is domain knowledge. In particular, when working with this dataset,  it is important to have background information about the organization, San Francisco Public Library (SFPL). 
## What do we know about driving forces behind library activities? 
* Here, defined as number of checkouts and may number of renewals
* Ideally, we can find literature about studies done in the area of public libraries. If there is none, a broader scope (which covers all kind of libraries) will be used. 
* In LISTA, the most useful subject term is "LIBRARY circulation analysis". At the first glance, it does look like it is more being done in academic libraries 

Works Cited

Comito, Lauren. “DPL, SFPL Offer Innovative Homeless Services.” Library Journal, vol. 140, no. 17, Oct. 2015, pp. 13–16. EBSCOhost, search.ebscohost.com/login.aspx?direct=true&db=lxh&AN=110530174&site=ehost-live.

Galbi, DouglasA. “Book Circulation Per U.S. Public Library User Since 1856.” Public Library Quarterly, vol. 27, no. 4, Dec. 2008, pp. 351–371. EBSCOhost, doi:10.1080/01616840802477144.

Landgraf, Mary N. “Library Cards for the Homeless.” American Libraries, vol. 22, no. 10, Nov. 1991, p. 946. EBSCOhost, search.ebscohost.com/login.aspx?direct=true&db=lxh&AN=9112233292&site=ehost-live.

Lilienthal, Stephen M. “The Problem Is Not the Homeless.” Library Journal, vol. 136, no. 11, June 2011, pp. 30–34. EBSCOhost, search.ebscohost.com/login.aspx?direct=true&db=lxh&AN=61428299&site=ehost-live.

Luzius, Jeff. “A Look at Circulation Statistics.” Journal of Access Services, vol. 2, no. 4, Jan. 2005, pp. 15–22. EBSCOhost, doi:10.1300/J204v02n04_03.
