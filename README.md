# Suma Wealth Technical Test: Email Marketing Analysis

In this exhaustive analysis, we will delve deep into user behavior in our email marketing campaigns. We will investigate how they interact with our emails, from open rates to conversions. Additionally, we will closely examine their purchasing patterns, identifying trends, preferences, and key opportunities. This analysis will provide us with valuable insights into how our customers engage with our email communications and how this translates into buying decisions. We will use this knowledge to optimize our marketing strategies and deliver an even more personalized experience to our users.

## Data Dictionary

### Users Data

- **customer_id**: Unique identifier for each customer.
- **awg_engagement_rate**: Average engagement rate of the user on posts.
- **comment_engagement_rate**: Engagement rate related to commenting on posts.
- **like_engagement_rate**: Engagement rate related to liking posts.
- **likes**: Total number of likes given by the user.
- **create_time**: The timestamp when the user's account was created.
- **full_name**: Full name of the user.
- **past_communications**: Number of times the user has received emails in the past.

### Emails Data

- **email_id**: Unique identifier for each email.
- **email_type**: Type of email, can be "soft" or "aggressive".
- **campaign_id**: The ID linking the email to a campaign in the campaigns table.
- **word_count**: Number of words in the email content.
- **total_links**: Total number of links in the email.
- **total_images**: Total number of images in the email.
- **email_status**: Status of the email, 0 for ignored, 1 for read, 2 for a purchase attributed to it.
- **customer_id**: Links to the user's ID in the users table.

### Campaigns Data

- **campaign_id**: Unique identifier for each campaign.
- **marketing_budget**: The budget used for the campaign.
- **month**: The month in which the campaign took place.

### Sales Data

- **month**: The month of the data record.
- **marketing_budget**: The budget allocated for marketing in the respective month.
- **sales**: The total sales revenue generated in the respective month.

## Sources:

1. [Email Marketing Data](https://www.kaggle.com/datasets/loveall/email-campaign-management-for-sme)
2. [Budget Data](https://www.kaggle.com/datasets/jacouchs/marketing-budget-and-actual-sales-dataset)
3. [Users Data](https://www.kaggle.com/datasets/manishkumar7432698/tiktok-profiles-data)

<small>\*Please note that the data used in this analysis is fictitious and should not be used to make real-world decisions.</small>
