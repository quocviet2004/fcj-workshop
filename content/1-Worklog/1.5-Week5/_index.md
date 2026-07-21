---
title: "Week 5 Worklog"
date: 2026-06-01
weight: 1
chapter: false
pre: " <b> 1.5. </b> "
---
{{% notice warning %}} 
⚠️ **Note:** The following information is for reference purposes only. Please **do not copy verbatim** for your own report, including this warning.
{{% /notice %}}


### Week 5 Objectives:

* Begin the development of the real-world project (**MINI Traveloka Booking Website**).
* Integrate AWS Lambda with Amazon DynamoDB using **AWS SDK for JavaScript v3** (`@aws-sdk/client-dynamodb`).

### Tasks to be completed this week:

| Day | Tasks | Start Date | Completion Date | References Material |
| --- | ----- | ---------- | --------------- | ---------- |
| 2 - 3 | - Initialized the backend project and installed the **AWS SDK for JavaScript v3** libraries. | 01/06/2026 | 02/06/2026 | <https://docs.aws.amazon.com/sdk-for-javascript/v3/developer-guide/welcome.html> |
| 4 - 5 | - Connected the AWS Lambda function to the `Hotels` table in Amazon DynamoDB created in Week 3. | 03/06/2026 | 04/06/2026 | <https://cloudjourney.awsstudygroup.com/> |
| 6 - 7 | - Implemented the `getHotelsList` function using `ScanCommand` to retrieve the list of hotels from Amazon DynamoDB. | 05/06/2026 | 06/06/2026 | <https://cloudjourney.awsstudygroup.com/> |

### Week 5 Achievements:

* Successfully completed the Node.js script for AWS Lambda and used `ScanCommand` to query data from Amazon DynamoDB.

### Week 5 Evidence:

![ScanCommand implementation using AWS SDK for JavaScript v3](/images/1-Worklog/1.5-Week5/lambda-dynamodb-code.png)