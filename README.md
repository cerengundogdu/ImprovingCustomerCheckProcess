### Project Name

Improving Customer Check Process 


### Business Problem and Dataset

According to Financial Conduct Authority (FCA) regulations, the financial company has to verify the identity of all customers who want to open an account. The person who wants to open an account has to submit a government-issued photo ID and a facial picture to Veritas. Veritas then would perform two checks “Document Check” to verify that the photo ID is valid and authentic and “Facial Similarity Check” to verify that the face in the picture is the same as that on the submitted ID.

The customer will “pass” the checking process and get onboarded if the results of both Document and Facial Similarity checks are “clear”. If the result of any check is not “clear”, the customer has to submit all the photos again.

The “pass rate” is defined as the number of customers who pass both the checking process divided by the number of customers who attempt the process. Each customer has up to 2 attempts. The pass rate has decreased substantially in the recent period. This report has been written to analyze the reasons behind this decrease and to make suggestions regarding the problem. 

The document report is composed of data integrity, visual authenticity and police record checks. It checks the internal and external consistency of the most recent identity document provided by the applicant to identify potential discrepancies. The facial similarity check will compare the most recent live photo or live video provided by the applicant to the photo in the most recent identity document provided.

The dataset includes the date between 23.05.2017 and 31.10.2017, which is approximately a  five-month period. Each row refers to one prospective customer who attempts to open an account. Some “user_id”s could be repeated since each customer has a right to apply up to 2 attempts. 


