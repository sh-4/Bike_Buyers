# Bike_Buyers

## Overview

The purpose of this repository is to look at what factors may go in to determining whether or not a customer opts to purchase a bike. The dashboard displayed below is interactive upon downloading the Bike Buyers Data Excel Sheet in the main branch.

![bikes_sales_dashboard](https://user-images.githubusercontent.com/105808695/205102918-696bd612-8ba3-4777-86a8-673957d369fd.png)


## Data Preprocessing

- Duplicate rows were removed
- Column values were adjusted for the visualizations
    - Marital Status: M/S --> Married/Single
    - Gender: M/F --> Male/Female
- Income decimals removed for a more polished looking income number
- New column created for Age Brackets, using a nested IF statement
    - Varying individual ages with a large range --> 3 age group categories (Young, Middle Aged, Older)
- Reformatted the Commute Distance Column Values for sequential ordering in the visualizations
    - "10+ Miles" --> "More than 10 Miles"

## Results

### Original Dashboard Results

![income_gender](https://user-images.githubusercontent.com/105808695/205103046-28c2d202-a4fc-4bca-85b9-87d036ca49e9.png)

The average income was higher for males than it was for females for both customers who purchased bikes, and those who did not.

![customers_agegroup](https://user-images.githubusercontent.com/105808695/205103116-27f18052-92fe-426a-810f-4a7da6da45d2.png)

Adults ages 31-54 purchased more bikes than those both younger and older.

![customer_commute](https://user-images.githubusercontent.com/105808695/205103161-b744a105-4d76-49c2-a062-73d88263a563.png)

More customers purchased a bike when they had a commute of 1 mile or less. However, those who opted to not purchase a bike also had the highest number in the 0-1 mile commute distance. Due to the spike in bike purchases from customers who had a daily commute of 2-5 miles, it's difficult to determine whether or not commute distance was a big contributing factor for these purchases. 

### Additional Filter Results

#### Marital Status

**Married**

![married_income](https://user-images.githubusercontent.com/105808695/205103262-6269677f-bd74-4fa5-8886-8f19b9564a48.png)

**Single**

![single_income](https://user-images.githubusercontent.com/105808695/205103278-41f5e1cb-e050-4c3f-9afa-581f986fe061.png)

Customers who were married had higher incomes than those who were single, regardless of whether or not they purchased a bike.

**Married**

![married_commute](https://user-images.githubusercontent.com/105808695/205103295-aab46150-80c9-44c4-b04e-7aef9c2cc313.png)

**Single**

![single_commute](https://user-images.githubusercontent.com/105808695/205103328-a5999aba-fff4-4528-8282-dffe68f904b1.png)

However, there were less single customers who opted not to purchase a bike than those who were married.

#### Education

![bachelors_commute](https://user-images.githubusercontent.com/105808695/205103449-29662363-1aef-45a6-8471-6fca2f84c34b.png)

Customers who earned a Bachelor's degree appeared to be more likely to have purchased a bike, regardless of if their commute was up to 10 miles in distance. 

![bachelors_agegroup](https://user-images.githubusercontent.com/105808695/205103469-9733be7f-e287-4854-985c-ef417dd20ce6.png)

Most of the people with Bachelor's degrees who purchased a bike were middle aged.

#### Home Ownership

**Home Owners**

![home_owner_commute](https://user-images.githubusercontent.com/105808695/205103548-98ae629b-9c7d-4b85-825b-a73e02f5bd10.png)

**Non Home Owners**

![non_home_owner_commute](https://user-images.githubusercontent.com/105808695/205103568-b32d29df-b7fe-49e7-acfb-55c029de79e7.png)

Home owners were more likely to purchase bikes than non home owners. Additionally, the number of bikes purchased by home owners are much higher up to a commute of 10 miles than those who do not own their own home.

## Recommendations

Since it is unclear whether or not the purchase of the bike was solely for a commute, more data will be needed to draw conclusive results. A recommendation for anyone wishing to repeat the study to gather the data would be to add a question about the purpose of the bike purchase: travel/commute, leisure/play, exercise, sport.
