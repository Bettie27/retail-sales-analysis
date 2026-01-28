# Retail Sales Analysis: What’s Driving Growth, Where Risk Is Building, and Why It Matters

**Audience:** Head of Retail / Commercial Manager

**Purpose**

This analysis reviews retail performance across revenue growth, demand behaviour, pricing, category mix, and store performance to support commercial and operational decisions. The focus is on identifying what is driving results today, where risk is accumulating, and which actions are justified.

**Data**

Anonymised transaction-level retail data covering multiple stores and product categories (2022–2025), including sales value, units sold, transactions, and realised prices.

**Approach**

Performance is assessed through trend analysis, price-versus-volume comparisons, and benchmarking of stores within comparable formats to separate structural drivers from seasonal effects.

**Headline conclusions**

* Revenue growth is increasingly price-led rather than demand-led, with rising prices offsetting declining volume and transactions.

* Pricing remains disciplined overall, with temporary promotional dips rather than sustained price erosion.

* Value is concentrated in bags and a small number of consistently strong stores, creating concentration risk.

* Demand is heavily concentrated on Saturdays, making overall performance more dependent on a limited number of peak days.

* Several stores underperform structurally, indicating positioning and execution issues rather than timing effects.

**Bottom line**

The business is growing, but becoming more fragile. Revenue is increasingly driven by price, a narrow set of categories, a small number of high-performing stores, and a limited set of peak-demand days.


> **How to read this project**
>
> - If you are interested in the insights and conclusions, this README provides a complete narrative.
> - If you are interested in the full analytical workflow, business questions, code, visuals and insights, refer to the Jupyter notebook in the `notebook/` directory.
>

## 1. Overall sales health: growth, volatility, and sustainability
<img width="1920" height="1080" alt="Screenshot 2026-01-28 112418" src="https://github.com/user-attachments/assets/2ca0aedb-7a7d-427c-be76-753ffdb17a31" />
<img width="908" height="472" alt="Screenshot 2026-01-28 112523" src="https://github.com/user-attachments/assets/6543df8c-02ad-434b-b143-9f08ad64d6c4" />
Monthly sales are highly seasonal, with a recurring November–December peak each year. While month-to-month volatility is high, peak sales levels rise over time, indicating higher monetisation rather than smoother baseline demand. This establishes a growth pattern that depends on seasonal strength rather than consistent volume expansion.

Total sales grew +12% YoY, but growth is not demand-led.
Total volume declined −7%, with fewer units sold and fewer transactions. The avarage realized price +20.5% and sales per transaction +21%.

The business is generating more revenue per sale, not selling more units. Sustaining growth now requires either:

* **Stabilise or rebuild volume** by selling more items per visit, bringing customers back more often, or shifting sales toward higher-volume products, or
* **Continue price-led growth**, accepting weaker customer demand and heavier reliance on peak seasons.

### Growth mechanism: volume vs price
<img width="1920" height="1080" alt="Screenshot 2026-01-28 112810" src="https://github.com/user-attachments/assets/67dfa024-fe66-4c55-b3cb-975d789b3064" />
Before 2024, revenue growth moved in line with volume, indicating demand-led performance. From 2024 onward, revenue continues to grow even as volume declines, confirming a shift to price-led growth. This growth model is fragile: if customers resist further price increases, revenue will fall quickly because volume is no longer supporting growth.

## 2. Price trends and promotional impact
<img width="1919" height="713" alt="Screenshot 2026-01-28 113041" src="https://github.com/user-attachments/assets/5642a0bc-39d2-4882-9dd5-b1075650a7eb" />
Average realised prices trend upward over the period, with temporary declines concentrated in promotion-heavy months. Importantly, these promotions do not reset the underlying price level.

From early 2024 onward, prices remain consistently higher, reinforcing the earlier finding that revenue growth is no longer driven by selling more units. Instead, growth is increasingly supported by higher prices and what customers buy, which we examine next

## 3. Category & Product Mix: Where does revenue come from, and where is the risk?
<img width="1314" height="449" alt="Screenshot 2026-01-28 113255" src="https://github.com/user-attachments/assets/c8ed42a7-cbb9-4008-8f37-cc4de24e684a" />
Sales are highly concentrated in Bags, which generate **29% of revenue from only 13% of units sold**. Nearly one-third of revenue depends on a category that does not move high volumes, creating clear concentration risk. Any disruption in this category would have an immediate impact on the P&L.

At the other extreme, Blouses drive a large share of unit sales but contribute little to revenue, suggesting that high volume does not translate into meaningful value.

This polarised mix raises a key question: do these categories react differently to price changes, and where is pricing power actually coming from?

## 4. Category pricing response: Which categories can absorb price increases?
<img width="1898" height="585" alt="Screenshot 2026-01-28 113449" src="https://github.com/user-attachments/assets/787a7ecc-04ab-4958-9ed0-7472e2bf2bf2" />
<img width="1854" height="582" alt="Screenshot 2026-01-28 113521" src="https://github.com/user-attachments/assets/c7b7f45c-ff40-4e80-81c8-3c6f2bd23732" />
<img width="1835" height="569" alt="Screenshot 2026-01-28 113538" src="https://github.com/user-attachments/assets/e9c254ea-f22a-4be8-aab3-4ad154ba2ac8" />
Indexed price–volume analysis shows clear differences by category:

* **Bags** show strong pricing power: price increases did not lead to a material decline in volume.

* **Dresses** show moderate price sensitivity: volumes have softened as prices rose, but demand has not collapsed.

* **Blouses** are highly price-sensitive: price increases were followed by sharp volume declines, indicating limited willingness to pay.

We next examine whether blouses rely on being bought together with other items rather than on being standalone.

## 5. Basket behaviour: why blouses respond differently to price
<img width="1413" height="908" alt="Screenshot 2026-01-28 113907" src="https://github.com/user-attachments/assets/9702614c-a9fc-4c61-b538-5955840ac6bc" />
Blouses appear in **16% of all baskets** (1,605 of 10,007 transactions), indicating frequent inclusion in customer purchases.

However, blouse purchases do not reliably expand basket value. **Nearly half of blouse baskets (767 of 1,605, ~48%)** contain only Blouses, showing limited cross-category attachment.

This basket behaviour helps explain the earlier price–volume result: when prices increase, volume drops sharply. Customers are willing to buy blouses at low prices, but demand falls quickly when prices rise.

Overall, Blouses function primarily as a traffic item rather than a value driver, explaining both their high price sensitivity and weak revenue contribution.

### **What this means for pricing decisions**
* **Bags:** Price increases are possible, but revenue is highly concentrated, making this category a key risk point.

* **Dresses:** Moderate price increases are possible, but rising price sensitivity means volume must be closely monitored.

* **Blouses:** Further price increases sharply reduce volume; value must come from being added to baskets rather than higher standalone prices.

## 6. Store performance and execution by format
<img width="1678" height="914" alt="Screenshot 2026-01-28 114240" src="https://github.com/user-attachments/assets/4de9b6ee-4bbe-456d-86a9-b2691cef2939" />
Stores are analysed within two distinct store groups: **clothes-led stores (Stores 1–3)** and **bags-led stores (Stores 4–6).**

At a group level, clothes-led stores drive 64% of total volume at an average price of 22.89, while bags-led stores drive 36% of volume at a much higher average price of 41.83. Despite this, both groups contribute roughly 50% of total revenue, confirming a premium, lower-velocity model in bags-led stores.

Importantly, performance is highly concentrated at the store level: Store_1 and Store_4 together account for 43% of total business revenue, making them the primary drivers of overall performance.

> Performance within the **bags-led group is highly uneven.**

Store_4 is a clear flagship, outperforming its group benchmark in **97%** of months, supported by both price discipline and consistent demand. By contrast, Store_5 and Store_6 underperform persistently.

Store_6 **maintains premium pricing** (price index ≈ 1.03) but suffers sharp demand weakness (volume index ≈ 0.71), indicating a **demand problem** rather than a pricing issue.

Store_5 **underperforms on both price and volume**, particularly in footwear, pointing to a broader mismatch between assortment and local demand.

> Clothes-led stores show **less dispersion.**

Store_1 consistently outperforms on volume, Store_3 tracks close to the group average, and Store_2 stands out for maintaining a higher price index (≈ 1.05) despite weak volume, suggesting a premium tilt without sufficient demand depth.

### How do different categories perform across stores?
<img width="1407" height="859" alt="Screenshot 2026-01-28 114522" src="https://github.com/user-attachments/assets/453ada11-875f-4dd1-910a-5376f5f17a7e" />
Within the bags-led group:

* Store_4 and Store_6 exhibit remarkably similar pricing architecture for bags and footwear, with average realised prices clustered around 66 for bags and 26–35 for shoes. The key difference is volume: Store_6 sells roughly half the units despite comparable pricing, confirming that its challenge is demand, not price.

* Store_5 differs structurally. While bag pricing is broadly aligned with the other bag-led stores, footwear pricing is significantly lower and contributes a larger share of sales. Combined with low overall volume, this suggests that both premium and volume strategies are failing, making Store_5 a candidate for fundamental repositioning.
<img width="1393" height="765" alt="Screenshot 2026-01-28 114625" src="https://github.com/user-attachments/assets/1f0ddf08-7540-4415-abcb-7c1d74fe7931" />
<img width="1453" height="479" alt="Screenshot 2026-01-28 114647" src="https://github.com/user-attachments/assets/0d67d44f-cb20-4701-a0ba-17899ffb5ac0" />
Within clothes-led stores:

* Store_2 reinforces its premium tilt through higher realised prices across dresses and jackets.

* Store_3 shows unusually high reliance on blouses, a low-value category, which raises margin and basket-quality concerns.

* Trouser suits in Store_3 and jackets in Store_2 underperform relative to peer stores, suggesting execution or assortment gaps rather than demand absence.

## 7. Demand patterns by day of week
<img width="1392" height="440" alt="image" src="https://github.com/user-attachments/assets/e07577fa-e443-491e-a0bc-fb644677d3a4" />
Demand is highly concentrated toward the end of the week, **with Friday and Saturday accounting for 35% of total weekly sales**. Saturday is the clear demand anchor, outperforming the weekly average across sales, volume, and transactions, indicating genuine demand rather than price-driven uplift.

By contrast, **Sunday consistently underperforms,** confirming that weekend demand is not evenly distributed. Midweek performance remains broadly stable.

As a result, **staffing, inventory, and new initiatives** should be stress-tested on Saturdays, not averaged across the week

## 8. Synthesis: What matters, what's risky and what to do next
**The 3 strongest performance drivers today**

1. **Price-led revenue growth** - Revenue growth is being sustained by higher realised prices rather than expanding demand. From 2024 onward, prices rise while volume and transactions decline, confirming a structural shift away from demand-led growth.

2. **Revenue is concentrated in Store_1 and Store_4** -These stores consistently outperform, while the others lag. This indicated the growth is driven by execution in a few locations, not broad-based improvement.

3. **Saturday is the demand anchor** - Nearly one-fifth of weekly sales occur on Saturday, driven by higher transactions and volume, not price inflation.

**The 3 biggest commercial risks if nothing changes**

1. **Silent volume erosion** - Revenue growth is increasingly disconnected from demand. Continued price increases without volume support create downside risk if price resistance emerges, especially in elastic categories.

2. **Revenue concentration risk** - Bags account for a disproportionate share of value with low unit velocity, concentrating P&L exposure in a narrow category and a small number of high-performing stores.

3. **Structural underperformance in specific stores** - Some stores (notably Store_5 and Store_6) are weak across months, indicating execution or positioning failures rather than timing or promotional issues.

**What management should do in the next 90 days**

1. **Be selective about price increases**

  * Keep current pricing in Bags, where higher prices have held without hurting demand.

  * Apply price increases cautiously in Dresses, where customer sensitivity is rising.

* Avoid further price increases in Blouses, where higher prices quickly reduce sales.

2. **Address underperforming stores at the root**

* Focus on building demand in Store_6 rather than adjusting prices.

* Reassess the role and positioning of Store_5, where both pricing and sales volumes are weak.

3. **Treat Blouses as a traffic driver, not a revenue lever**

* Blouses appear often in customer purchases but rarely increase basket size. Value should come from how they are combined with other items, not from higher standalone prices.











