# SfB-Call-Accounting
Skype for Business and Lync Call Accounting          

This script queries the SfB/Lync CDR database (LcsCDR), performing calculations on the data to provide you useful call billing information.

  *  Ability to bill based on users Active Directory department or company field 
  *  Import vendor rate cards to perform call rate and cost calculations 
  *  Import vendor gateways- Determines call direction - inbound, outbound, forwarded, SfB-to-SfB
  *  Handles billing of forwarded calls using the Referred-By information 

For more infomation and details on how to use the script please see my blog post - https://ucgeek.co/call-accounting/


# Version History
* V 0.2 - Feb 2014 - beta: 1st release   
* V 0.3 - Feb 2014 - beta: Moved data processing to SQL using temporay tables
* V 0.4 - Mar 2014 - beta: Moved functions outside of script
* V 0.5 - Mar 2014 - beta: Added vendor rate card lookup and csv gateway import  
* V 0.6 - Mar 2014 - beta: Added support for Lync 2010 Monitoring server reports  
* V 0.7 - Mar 2014 - beta: Removed requirement for vendor rate card and gateways csv. If RateCard.csv or Gateways.csv dont exist and empty table will be created.
* V 1.0 - Mar 2014 - beta: Added call cost calculations, commented SQL query, prepared restructured version for release    
* V 2.0 - June 2014 - stable: Minor bug fixes and improvements, tested in production for 3 months  
* V 2.1 - June 2014 - stable: Added better error checking, error output and debug mode


 

 

        
    
