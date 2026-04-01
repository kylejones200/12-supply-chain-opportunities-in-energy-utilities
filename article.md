# 12 Supply Chain Opportunities in Energy & Utilities Is it possible to have end-to-end supply chain visibility?

::::### 12 Supply Chain Opportunities in Energy & Utilities 

#### **Is it possible to have end-to-end supply chain visibility?**
The most basic question in supply chain initiatives for Energy &
Utilities is "where's my stuff?" A simple question that is actually
really hard to answer because it requires integrating data from Work
Orders, Schedules, and inventory.


<figcaption>Photo by <a
href="https://unsplash.com/@epicantus?utm_source=medium&amp;utm_medium=referral"
class="markup--anchor markup--figure-anchor"
data-href="https://unsplash.com/@epicantus?utm_source=medium&amp;utm_medium=referral"
rel="photo-creator noopener" target="_blank">Daria Nepriakhina 🇺🇦</a>
on <a
href="https://unsplash.com?utm_source=medium&amp;utm_medium=referral"
class="markup--anchor markup--figure-anchor"
data-href="https://unsplash.com?utm_source=medium&amp;utm_medium=referral"
rel="photo-source noopener" target="_blank">Unsplash</a></figcaption>


If we can find the "stuff" then the next question is about scenario
analysis --- what happens if there is an exogenous shock to the supply
chain. This could be a road flooding that causes a re-direct from the
supplier to the warehouse. Unfortunately, this is also a very tricky
problem for Energy & Utilities customers to address. \
 \
Here are eleven applications of supply chain solutions for Energy &
Utilities.

- Demand Forecasting: Companies predict when equipment will be needed
  based on history. The system makes explicit when certain items are
  ordered on a regular cadence like quarterly or yearly. Management uses
  this information to negotiate with suppliers for bulk discounts or
  just in time delivery.
- Track-And-Trace Data Hierarchies For Suppliers: This identifies
  suppliers who require long lead times or suppliers responsible for
  late deliverers. Management uses this renegotiate to renegotiate with
  suppliers or select alternative suppliers. This can also be called
  supplier segmentation.
- Analysis Of Machinery Performance: This uses the work orders to
  identify patterns in the maintenance required by each machine and
  grouped by equipment type and OEM. Management uses this to identify
  potential bad-actor suppliers or pieces of kit which require more
  maintenance than a benchmark. Additionally, AI/ML could predict
  remaining useful life (RUL) for machines or other predictive
  maintenance algorithm.
- Controlled access by suppliers (N-tier): Suppliers are given access
  to the system using a specific role with limited privileges. This
  allows suppliers to use their own mechanisms to predict when parts
  should be replaced without requiring direct access to Energy &
  Utilities customers systems. This facilitates collaboration between
  MSC and suppliers.
- Forecast new capital projects: Companies investing in new capital
  projects don't have historical data to use to make supply chain
  forecasts (called the "cold start" problem). Customers can use a proxy
  to provide guidance on what future projects should expect --- an
  analogue based on needs from similar projects. This would inform
  sparing decisions and initial inventory orders.
- Computer vision for inventory management: Most Energy & Utilities
  customers do not have an automated system to log when materials arrive
  at various checkpoints such as the warehouse or dockyard. Computer
  vision could automatically record when items arrive. There is no
  specific manifest created when materials are crated at the docks but a
  camera running computer vision at the edge could complete this task. A
  similar camera could also be used to scan warehouse shelves and
  provide an estimate of existing inventory.
- Limiter reduction for improving performance: Energy & Utilities
  customers provides specific KPIs for measuring performance and the
  system tacks these and displays results on simple dashboard. The
  objective is to identify the true constraints (or limiters) which are
  associated with displays or increased costs.
- Running "cost of current inventory" tracker: a tracker/sign that
  displays the cumulative sum of the equipment currently in the
  warehouse. It also displays the leverage amount of time an item
  remains in the warehouse and the max time a current item has spent in
  the warehouse.
- Tracking Logistics Advisor effectiveness: The system tracks KPIs for
  individual performance such as the cost of goods returned, the number
  of changes made, the proportion of on-time deliveries.
- Sandbag metrics: the system tracks when too much inventory is on hand
  based on equipment strategies. For example, the documented equipment
  strategies set expectations for replacement capacity such as 80% for
  non-critical equipment. This means that 20% of the time, Energy &
  Utilities customers should not have the replacement part. Equipment
  operating at a reliability level above the equipment strategy is
  flagged for management review because it is likely being over
  maintained.
- [[Pattern matching in Work
  Order](https://aws.amazon.com/blogs/supply-chain/mitigating-operational-risks-with-aws-supply-chain-work-order-insights/)s: We use AI/ML + Gen AI to identify
  work orders which are similar or happen concurrently. This is used to
  pre-populate work orders and automatically trigger
  dependencies --- for example, if every time the compressor take
  pressure valve is replaced they also replace the filters then issuing
  a work oder for the pressure valve would automatically trigger a work
  order for the filter.]
- [[Equipment and Sparing
  strategy](https://aws.amazon.com/blogs/supply-chain/aws-offerings-for-visibility-and-on-time-arrival-of-maintenance-spares-for-mining-and-energy/): Using customer supply chain data, we
  can analyze the equipment and sparing strategy to determine if they
  are following their own internal guidances. How much of the spares
  they use, average "dwell time" for spares (how long spares remain in
  warehouse and carrying cost for spares). This provides insights into
  the inefficiencies of the supply chain. Once identified, management
  can target the issue areas (limiters) and reduce them --- thus
  improving the supply chain. Energy & Utilities customers benefit from
  this because it shows how much cash is tied up in inventory and the
  solution informs how capital projects should be executed/how many
  spares are needed in the future.]

[**AWS offerings for visibility and on-time arrival of maintenance
spares for mining and energy \|...**\
*The aim of any inbound supply chain for materials is to make sure that
spare parts, rotable spares, and
consumables...*aws.amazon.com](https://aws.amazon.com/blogs/supply-chain/aws-offerings-for-visibility-and-on-time-arrival-of-maintenance-spares-for-mining-and-energy/ "https://aws.amazon.com/blogs/supply-chain/aws-offerings-for-visibility-and-on-time-arrival-of-maintenance-spares-for-mining-and-energy/")[](https://aws.amazon.com/blogs/supply-chain/aws-offerings-for-visibility-and-on-time-arrival-of-maintenance-spares-for-mining-and-energy/)
All Energy & Utilities customers run supply chain. And every supply
chain can be improved. These are 12 areas where smarter supply chain
technology can reduce costs and increase predictability so that
operators can find/track/use/optimize their "stuff."

### Related Stories
- [[Navigating the Complexities of SAP for Energy &
  Utilities](https://medium.com/@kylejones_47003/navigating-the-complexities-of-sap-for-energy-utilities-e8d60201cfc8)]
- [[SCADA on AWS: Architectural Approaches for Security and Resilience
  Control
  Systems](https://medium.com/@kylejones_47003/scada-systems-to-the-aws-cloud-architectural-approaches-for-enhanced-security-and-resilience-9d97878eb53e)]
- [[Modernizing High-Performance Computing for the Power Grid:
  Leveraging AWS to Enable
  Scalable...](https://medium.com/@kylejones_47003/modernizing-high-performance-computing-for-the-power-grid-leveraging-aws-to-enable-scalable-516944d7ac14)]
::::::::::::By [Kyle Jones](https://medium.com/@kyle-t-jones) on
[September 13, 2024](https://medium.com/p/6794edf52aa8).

[Canonical
link](https://medium.com/@kyle-t-jones/12-supply-chain-opportunities-in-energy-utilities-6794edf52aa8)

Exported from [Medium](https://medium.com) on November 10, 2025.
