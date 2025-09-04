# FedEx-Logistics-Performance-Analysis

**Optimizing FedEx Logistics Through Data Analysis**
In today’s fast-paced, globally connected market, FedEx Logistics plays a pivotal role in managing supply chains across various industries and regions. With the rapid growth of eCommerce and global distribution networks, maintaining efficient logistics operations is critical to staying competitive. This project focuses on analyzing data from FedEx Logistics to uncover insights that can optimize shipment processes, minimize costs, and enhance customer satisfaction. The dataset contains information on shipment modes, countries, vendors, line item values, weights, freight costs, delivery delays, and more, allowing for a comprehensive analysis of the company’s logistics performanctisfaction.

**Univariate Analysis**

**1. Count of Shipments by Country:**

This analysis revealed the distribution of shipments across various countries, helping identify key markets. Countries with the highest shipment volumes represent regions where FedEx may need to allocate more resources to maintain operational efficiency.

**2. Distribution of Shipment Modes:**

Analyzing shipment modes (e.g., Air, Sea, or Ground) showed that air shipments, though faster, were less frequently used due to their higher costs, while sea shipments were more common but associated with longer delivery times. This insight is crucial for balancing cost and speed.

**3. Average Freight Cost:**

The average freight cost per shipment provided insights into the overall cost structure, highlighting the need to optimize the more expensive modes of transport, such as air.

**4. Line Item Quantity Distribution:**

Visualizing the distribution of line item quantities showed that most shipments contained smaller quantities, with larger shipments being less frequent. This can inform future inventory management strategies and order consolidation efforts.

**5. Weight Distribution:**

The weight distribution analysis showed a wide range of shipment weights, indicating the varying scale of deliveries. Heavier shipments tend to incur higher freight costs, emphasizing the need to optimize the shipment of bulk goods.

**6. Vendors with Highest Orders:**

This analysis identified vendors that contributed the most shipments. Understanding which vendors generate the highest order volumes allows FedEx to prioritize relationships and streamline vendor-specific operations.

**Bi-variate Analysis:**

**1. Average Weight by Shipment Mode:**

Comparing the average weight across different shipment modes provided valuable insights into how shipment methods impact weight handling. Sea shipments, for example, typically handled much heavier loads compared to air shipments, which aligns with cost expectations.

**2. Delivery Delays by Shipment Mode:**

Analyzing delivery delays by shipment mode highlighted that air shipments were the least likely to experience delays, while sea shipments often had longer lead times. This data can guide decisions about which shipment mode to use for time-sensitive deliveries.

**3. Total Shipments Over Time:**

By tracking the number of shipments over time, this analysis revealed seasonal trends and fluctuations in demand. Identifying peak shipping periods enables FedEx to allocate resources effectively during high-demand seasons.

**4. Line Item Value Across Different Shipment Modes:**

This comparison showed how the value of items shipped varies by the mode of transport. High-value items were often shipped via air due to their time-sensitive nature, while lower-value goods were more commonly transported via sea or ground.

**Multi-variate Analysis:**

**1. Freight Cost by Country, Shipment Mode, and Vendor:**

A multivariate analysis of freight costs revealed significant variations across different countries, shipment modes, and vendors. For example, certain vendors in high-cost regions showed consistently higher freight costs, offering opportunities to renegotiate vendor agreements or explore alternative shipping methods.

**2. Line Item Value vs. Freight Cost by Vendor and Shipment Mode:**

This analysis showed that for some vendors, freight costs were disproportionately high relative to the value of the items being shipped. This could indicate inefficiencies or opportunities for cost reduction, especially in optimizing shipping modes for specific vendors.

**3. Correlation Heatmap:**

A correlation heatmap of numerical variables revealed strong relationships between shipment weight, freight cost, and line item value. This information helps identify which variables have the greatest influence on freight costs, aiding in cost optimization efforts.

**4. Pair Plot:**

A pair plot visualizing relationships between variables like line item value, freight cost, and shipment weight showed how these variables interact. This analysis highlighted clusters of shipments that shared similar e costs, and improve customer satisfaction across its operations.

# **Problem Statement**

The dataset aims to optimize FedEx Logistics' global supply chain by providing detailed insights into purchase orders, shipment methods, vendor agreements, and delivery schedules. With the rise of eCommerce and increasing global distribution demands, analyzing this data will help identify bottlenecks, minimize freight costs, and enhance delivery efficiency. The goal is to streamline operations, improve customer satisfaction, and maintain a competitive edge by ensuring timely deliveries and cost-effective logistics management.

# **Business Objective**

The business objective is to optimize FedEx Logistics' global supply chain operations by leveraging data insights to improve delivery efficiency, reduce shipping costs, and enhance customer satisfaction. The goal is to identify bottlenecks, streamline processes, and ensure timely and cost-effective deliveries across various regions and industries. This will support FedEx in maintaining a competitive edge in the growing eCommerce and global distribution landscape while delivering value to both the company and its customers.

### Import Libraries

*   Pandas
*   Matplotlib
*   Seaborn
*   plotly
