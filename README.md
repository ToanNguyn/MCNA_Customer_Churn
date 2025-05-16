# MCNA_Customer_Churn
| Feature                    | Description                                                                                             |
| -------------------------- | ------------------------------------------------------------------------------------------------------- |
| **State**                  | The U.S. state (abbreviation) where the customer lives (e.g., `CA` = California).                       |
| **Account length**         | How long the customer has been with the company (in days or months). Can reflect customer loyalty.      |
| **Area code**              | Telephone area code, representing the customer’s geographical region.                                   |
| **International plan**     | Whether the customer has subscribed to an international calling plan (`Yes` or `No`).                   |
| **Voice mail plan**        | Whether the customer has a voice mail service (`Yes` or `No`).                                          |
| **Number vmail messages**  | Number of voice mail messages the customer has. Likely greater than 0 if they have the voice mail plan. |
| **Total day minutes**      | Total number of minutes spent on calls during the **daytime**.                                          |
| **Total day calls**        | Total number of **calls** made during the daytime.                                                      |
| **Total day charge**       | Total charge for daytime calls. (Usually calculated as minutes × rate.)                                 |
| **Total eve minutes**      | Total call minutes during the **evening**.                                                              |
| **Total eve calls**        | Number of calls during the evening.                                                                     |
| **Total eve charge**       | Total charge for evening calls.                                                                         |
| **Total night minutes**    | Total call minutes during the **night**.                                                                |
| **Total night calls**      | Number of calls made at night.                                                                          |
| **Total night charge**     | Total charge for night-time calls.                                                                      |
| **Total intl minutes**     | Total number of **international** call minutes.                                                         |
| **Total intl calls**       | Total number of international calls.                                                                    |
| **Total intl charge**      | Total cost of international calls.                                                                      |
| **Customer service calls** | Number of times the customer called **customer support**. High numbers may indicate dissatisfaction.    |
| **Churn**                  | **Target variable**: whether the customer left the service (`Yes`) or stayed (`No`).                    |
