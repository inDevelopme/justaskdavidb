# Introduction to the CAP Theorem    
We will explore what the CAP Theorem does and learn about each of the three essential aspects in it!  
## What is the CAP Theorem?
The main idea behind the CAP Theorem is that trade-offs need to be made in order to utilize our system or database most effectively during network failure.  

To achieve this, we must focus our efforts on the most important aspects of our particular system.   
-  The CAP Theorem contains three fundamental aspects:
  
    -    **Consistency**    
    -    **Availability**    
    -    **Partition-Tolerance**.
    
-  This is what CAP stands for!
## Consistency
Show the **same, updated** information to all clients     
-  Information must be consistent throughout all users viewing the data, with *no* discrepancies between users.       
-  Consistency becomes vital when:
  
     -   the data within our system is too valuable or important to be changed
     -   or when the importance of the data itself depends on how accurate, updated, and consistent the data is.      

## Availability
Being able to **access** data, or data availability    

Although data might not be the most updated, data can be undoubtedly accessed, even if part of the system is down.   

-  This is important when data accessibility needs to be prioritized, *even more* than the updated actual content of the data itself.  

## Partition-Tolerance  
The **most important aspect** award (in the CAP Theorem) easily belongs to Partition-Tolerance.    

-  Partition Tolerance ***must be prioritized*** in order to have a functional system.  

-  Partition tolerance means that the system itself still works even after network failure, when communications within our network/system stop working.
## Uses and Combinations of the Aspects  

### CP databases (consistency and partition-tolerance)  
Prioritizes consistency, or showing the same information to all clients  
-  Very appealing for services such as banks or messages

    -  Data needs to be very accurate and updated to everyone.
-  Some databases that prioritize consistency are MongoDB, Redis, and Hbase.  

### AP databases (availability and partition-tolerance)    
Prioritizes availability, or access to data  

Used for services that would lose revenue or suffer a large loss from being down for maintenance  

Uses or display old data temporarily while they fix their system to show updated data again.

 -  In order for this to work, the outdated data must：

     -   not be too different from the new, updated data  
     -   be close enough to the original data so that operations will not be disrupted.

-  An online shop might use an AP database, since availability would take precedence over consistency here when updating.  
    -  Many system updates would prioritize availability over consistency,

        -   especially if the updates would take too long to roll out to everyone but are not important enough to warrant shutting down the entire system for maintenance.

-  Some databases that prioritize accessibility are Cassandra, DynamoDB, and Cosmos DB.
### CA databases (consistency and availability)  

**Infeasible** because partition-tolerance is the most important aspect of a system  

-  Operation of the system itself is much more important than the other two aspects, which enhance the features and functionality of the system.

CA databases only exist in theory and are currently **unusable**
##  Conclusion
The CAP Theorem shows us what to prioritize during network failure, when our system goes down.  

-  Extremely important for the efficiency of varying online services

-  The functionality of vital online services also depends the CAP Theorem

-  Without the CAP Theorem, clients would have a difficulty using online services, resulting in a less advanced Internet
