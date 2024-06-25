# FINAL PROJECT (A/B TESTING): EVALUATING THE IMPACT OF AN ENHANCED RECOMMENDATION SYSTEM THROUGH A/B TESTING
# Data
- final_ab_events_us.csv: Contains all events of new users within the test period.
> - user_id: Identifier of the user.
> - event_dt: Date and time of the event.
> - event_name: Type of event (e.g., product_page, product_cart, purchase).
> - details: Additional data on the event (e.g., order total in USD for purchase events).

- final_ab_new_users_us.csv: Contains all users who signed up from December 7 to 21, 2020.
> - user_id: Identifier of the user.
> - first_date: Sign-up date.
> - region: Region of the user.
> - device: Device used to sign up.

- final_ab_participants_us.csv: Contains the test participants.
> - user_id: Identifier of the user.
> - ab_test: Name of the A/B test.
> - group: Test group the user belonged to (A or B).

- ab_project_marketing_events_us.csv: Contains the calendar of marketing events for 2020.
> - name: Name of the marketing event.
> - regions: Regions where the ad campaign was held.
> - start_dt: Campaign start date.
> - finish_dt: Campaign end date.

# Goal
> - To boost user engagement by enhancing product page views, cart adds, and purchases by at least 10% in the Variation B group compared to the Control A group.
> - To analyze the impact of the new recommendation system on conversion rates at critical stages of the sales funnel.
> - To apply the results of the A/B test to decide on the full-scale implementation of the new recommendation system.

# Libraries
*pandas , math, matplotlib ,numpy, seaborn, nltk, scipy, scipy.stats, plotly.graph_objects*
