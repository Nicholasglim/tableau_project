# This project explores of Tableau Global Superstore Dataset and key insights derived.
View the dashboard on Tableau Public: https://public.tableau.com/views/GlobalSuperstoreVisuals_17521321423280/Story?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

## Key Findings: Redundant shipping mode & product returns are eating into the company's profits
**1. Redundant shipping mode**
![image](https://github.com/user-attachments/assets/cfd3050c-e4e8-49da-a9e5-7cefbab59d24)
Proposed change: **Remove Ship Mode (First-class)**

* From time of receiving the order to shipping the order, the time to ship for all three priority modes (Critical, High, & Medium) is **two days on average. Additionally, Order Priority (High) arrive slightly earlier on average, compared to Order Priority (Critical)
* While the time to ship for Ship Mode (Second-class) are **2.3 days** (Critical Priority), **2.9 days** (High Priority), & **3.8 days** (Medium Priority), are more indicative to their associated priority.
* By replacing Ship Mode (First-class) with Ship Mode (Second-class), shipping cost can be reduced by **6.75%** (Critical Priortity), **19.48%** (High Priority), & **25.52%** (Medium Priority)

**2. Product returns**
![image](https://github.com/user-attachments/assets/69ff0a1f-a039-4502-8ac9-c5f37b81f949)
According to the map shown above, the areas coloured in green are shown to be profitable. Namely, market segments such as Canada, Africa, EMEA (Representing the Middle East, Central Asia, and Russia), are areas without data of product returns. However, there are some exceptions that where the profit ratio are close to zero or even negative.

On the other hand, the majority of areas in the US, LATAM (Latin America), EU, & APAC, have a profit ratio close to zero, with some exceptions that are in the negatives or above 0.2.

![image](https://github.com/user-attachments/assets/c07331a8-1efb-495d-881f-bd9fcf275c9b)
All the top 10 countries, in terms of profitability have a profit ratio close to zero.

* The US
* LATAM (Mexico & El Salvador)
* Europe (United Kingdom, France, Germany, & Spain)
* APAC (China, India, & Australia)

### Year-on-Year Returns by Market Segment
|      | APAC |  EU  | LATAM | US |Grand Total
| :--: | :--: | :--: | :--: | :--: | :--: |
| **2011** | 105  |   59 |  88  | 86  | 338 | 338 |
| **2012** | 115  |   93 |  119 | 108 | 435 | 435 |
| **2013** | 118  |  123 |  144 | 116 | 501 | 501 |
| **2014** | 166  | 153  | 148  | 186 | 653 | 653 |
|**Grand Total**| 504  | 428  | 499  | 496 | 1927 |

Findings show that the number of returns increases year-on-year. 

*	From 2011 to 2012, there was a 28.7% increase in returns.
*	From 2012 to 2013, there was a 15.17% increase in returns.
*	From 2013 to 2014, there was a 30.34% increase in returns. 

![image](https://github.com/user-attachments/assets/d00c42fc-6be7-4408-8a3c-8120c7881232)
Findings show that product returns increase as it goes down the different Ship Modes (Same Day > First-class > Second-class > Standard-class)
