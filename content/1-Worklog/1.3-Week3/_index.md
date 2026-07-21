---
title: "Week 3 Worklog"
date: 2026-05-18
weight: 1
chapter: false
pre: " <b> 1.3. </b> "
---
{{% notice warning %}} 
⚠️ **Note:** The following information is for reference purposes only. Please **do not copy verbatim** for your own report, including this warning.
{{% /notice %}}


### Week 3 Objectives:

* Designed the NoSQL database on Amazon DynamoDB.
* Defined the JSON data structure for the core tables (`Hotels`, `Users`) and imported sample data.

### Tasks to be carried out this week:
| Day | Task                                                                                                                                                                                                   | Start Date | Completion Date | Reference Material                        |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------- | --------------- | ----------------------------------------- |
| 2 - 3 | - Created the `Hotels` and `Users` tables in Amazon DynamoDB.<br>- Defined the Primary Key (Partition Key) and Sort Key to optimize query performance for the room search feature. | 18/05/2026 | 19/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 4 - 5 | - Configured the read/write capacity (RCU/WCU) within the AWS Free Tier to optimize costs.<br>- Prepared a sample JSON file structure containing hotel room information (Name, Price, Image URL, Amenities). | 20/05/2026 | 21/05/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 6 - 7 | - Used the **Explore table items** feature to insert sample hotel room data into the database.<br>- Verified queries to ensure the data was displayed correctly. | 22/05/2026 | 23/05/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Week 3 Achievements:
* Successfully completed the NoSQL database structure for the **MINI Traveloka Booking** application on Amazon DynamoDB.
* Populated the database tables with sample hotel room data, making them ready for API integration in the following week.
* Gained a solid understanding of Partition Key design and efficient data access without relying on traditional SQL queries.

### Week 3 Evidence:
![Hotels table in Amazon DynamoDB](/images/1-Worklog/1.3-Week3/dynamodb-hotels.png)