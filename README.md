***

# Customer Churn Analysis Project (Python)

## Short Description / Purpose

This project digs into the story behind why some customers decide to leave a service. Using Python and popular data science libraries, it paints a clear picture of customer behavior and churn patterns. The goal is simple: help businesses understand what’s driving people away so they can keep more customers happy and loyal.

## Project Objective

At its core, this project answers straightforward questions: Who is more likely to leave? When do most customers churn? What role do contract terms, payment methods, and extra services play? By turning data into easy-to-grasp insights, the project gives companies a map to reduce churn and build stronger relationships with their customers.

## [Dataset Used](https://github.com/akramaftab/python-customer-churn-analysis/blob/main/Customer%20Churn%20data.csv)

The analysis works with a detailed dataset of over 7,000 customers, tracking information like:
- Customer demographics and subscription details
- Contract types: over half are on month-to-month deals, while the rest have 1- or 2-year contracts
- How they pay: from electronic checks to credit cards and bank transfers
- How long they stay (from 0 up to 6 years)
- What services they're using, like online security, tech support, or streaming
- Most importantly, whether they eventually churn or stay

## Key Questions (KPIs)

- What share of customers are actually leaving?
- Are men or women more likely to churn?
- How does age or senior citizen status affect loyalty?
- When in their subscription life are people most at risk of leaving?
- Do contract lengths change how many customers leave?
- Does paying by check or card make a difference?
- Which extra services help keep customers around longer?
- How much churn can we realistically prevent?

## Process

The data is cleaned and explored using Python—calculating percentages, drawing charts, and finding patterns. We then translate numbers into clear, relatable stories that make the insights easy to understand and act upon.

### Visualization & Interaction

All of the analysis and charts can be viewed in Jupyter Notebooks, making it easy to explore the data and walk through the story behind the numbers.

## What We Found (Summary KPIs)

| Measure                                   | Figure                            |
|-------------------------------------------|---------------------------------|
| Total Customers                          | 7,043                           |
| Overall Churn Rate                       | About 26.5% (or roughly 1 in 4) |
| Churn Rate by Gender                     | Women slightly lower (26.1%) than men (27.1%) |
| Churn Rate for Senior Citizens           | Much higher at 35%               |
| Early Churn (first 3 months)             | A striking 41% of churn happens here |
| Contract Types Distribution              | 55.5% month-to-month, 29.5% one year, 15% two year |
| Churn Rate by Contract                   | Month-to-month highest at 42.5%; just 4.5% for two-year contracts |
| Payment Method Breakdown                 | 33% electronic check, 27% bank transfer, 20% credit card, 20% mailed check |
| Churn Rate by Payment Method             | Electronic checks churn at 43%, way above the rest |
| Impact of Extra Services                  | Customers without online security are more than twice as likely to quit (35% churn vs 15%) |
| Tech support users churn 12% less often  |                                 |

## Key Takeaways & What This Means

- Almost **41% of customers who leave do so within the first three months**. This means the early months really make or break the customer relationship—focusing efforts here can pay huge dividends.
- Customers holding **month-to-month contracts are nearly 3 times more likely to leave** compared to those with longer-term contracts. Offering incentives to move these customers into yearly contracts could stabilize the business.
- Paying by **electronic check is a big red flag**, with churn rates hovering around 43%. Fixing payment issues here or offering more options could keep lots more customers happy.
- **Adding value through online security and tech support helps customers stick around**. Those users churn a lot less, showing that these services build trust and loyalty.
- Seniors are at higher risk - with a churn rate of **35%**, indicating the need for tailored care and attention to older customers.

## What Should We Do Next?

- Focus on the **critical first 90 days** to engage and support new customers so they stay longer.
- Create **incentives and offers to encourage longer contracts**, reducing churn substantially.
- Dive deeper into **payment experience improvements**, especially for electronic check users.
- Highlight and upsell **protective services like online security**, which truly make a difference.
- Tailor **special retention programs for senior customers** to lower their churn.

## Final Thoughts

This project brings hard data to life in a way that shows where and why customers leave, giving businesses the tools and insight to turn those numbers around. Instead of guessing, companies can now focus their energy where it matters most—keeping customers happy, engaged, and loyal.

## Tech Tools Used

- Python (Pandas to analyze data, Matplotlib and Seaborn to visualize)
- Jupyter Notebook for a smooth, interactive experience

## View Project Here

***


