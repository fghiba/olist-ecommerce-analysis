# olist-ecommerce-analysis
---

## Key Findings

### 1. Revenue grew 5x in 12 months — then plateaued

Monthly revenue climbed from R$63K in October 2016 to a peak of
R$1.56M in November 2017 — a 5x increase in under 14 months. From
January 2018 onward, revenue stabilised between R$1.2M and R$1.5M per
month with no further growth. This signals that the high-growth
acquisition phase has ended and the business now needs a retention or
new-channel strategy to resume scaling.

![Monthly Revenue & Order Volume](outputs/monthly_revenue.png)

---

### 2. Customer retention is critically low at 3%

Only 2,918 out of 97,585 orders (3%) came from repeat customers.
This is a known structural characteristic of marketplace models — after
a first purchase, buyers often establish a direct relationship with the
seller and bypass the platform entirely. From a business standpoint,
this means Olist's growth depends almost entirely on new customer
acquisition, making it expensive and fragile. A post-purchase loyalty
programme targeting high-AOV first-time buyers would directly address
this gap.

---

### 3. Bed & bath dominates revenue; watches command the highest price

Cama mesa banho (bed, bath & table linen) leads all categories at
R$1.71M in total revenue across 9,378 orders. However, relogios
presentes (watches & gifts) has the highest average item price at
R$200.51 — more than double the bed & bath average of R$93.40. This
means watches are a high-margin, lower-volume opportunity that deserves
targeted promotional investment.

| Category | Revenue | Avg Item Price |
|---|---|---|
| Bed, Bath & Table (cama_mesa_banho) | R$1.71M | R$93.40 |
| Beauty & Health (beleza_saude) | R$1.64M | R$130.05 |
| Computer Accessories (informatica_acessorios) | R$1.56M | R$116.07 |
| Watches & Gifts (relogios_presentes) | R$1.41M | R$200.51 |
| Furniture & Decor (moveis_decoracao) | R$1.41M | R$87.21 |

![Top 10 Product Categories by Revenue](outputs/top_categories.png)

---

### 4. Credit card accounts for 78.6% of all revenue

Credit card is the dominant payment method at 78.6% of revenue, with
boleto bancário (a Brazilian offline payment slip) second at 17.9%.
The remaining methods — vouchers and debit cards — account for under
4% combined. The heavy credit card skew is likely driven by
instalment payment options which are standard practice in Brazilian
e-commerce. Optimising the credit card checkout flow and expanding
instalment options would have the highest direct impact on conversion.

![Revenue Share by Payment Method](outputs/payment_methods.png)

---

### 5. 93.2% of orders delivered on time

6.8% of delivered orders (6,534 orders) arrived after the estimated
delivery date. While this is a strong overall number, late deliveries
on a marketplace disproportionately damage platform reputation — the
customer blames Olist, not the individual seller. Identifying which
product categories or seller regions drive the most delays would allow
targeted logistics improvements.

---

## How to Run

1. Download the Olist dataset from
   [Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
2. Place all CSV files in the same folder as the notebook
3. Open `analyze_olist.ipynb` in Google Colab or Jupyter
4. Run all cells top to bottom

> Note: The September 2018 data point in the monthly revenue chart
> reflects an incomplete month — the dataset ends mid-September 2018
> and should not be interpreted as a real revenue drop.

---

## Skills Demonstrated

- Multi-table data merging and cleaning with Pandas
- Time series revenue analysis
- Customer segmentation (new vs repeat)
- Payment behaviour analysis
- Delivery performance measurement
- Business insight communication from raw data
