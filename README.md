**Project Title: Optimizing Distribution Center Placement for a Food Retail Store using K-Means Clustering**

**Objective:**
This project aimed to strategically determine optimal locations for distribution centers in a food retail store. Utilizing the K-Means clustering algorithm on data obtained from the public API "GET https://data.ny.gov/api/views/9a8c-vfzj/rows.csv?accessType=DOWNLOAD," the goal was to efficiently cover geographical areas while considering both distance and density factors.

**Methodology:**
1. **Data Retrieval:**
   - Extracted essential geographical data from the public API to inform the clustering process.

2. **K-Means Clustering:**
   - Applied K-Means clustering to group geographical coordinates into clusters, representing potential distribution center locations.

3. **Density-Based Analysis:**
   - Incorporated density analysis to identify regions with high customer demand, optimizing distribution based on both geographical and plot density.

4. **Optimal Location Identification:**
   - Evaluated clustering results to determine optimal distribution center locations, minimizing distance and ensuring efficient coverage.

5. **Variable Distribution Centers (N):**
   - Implemented a variable parameter (N) to explore different scenarios, allowing flexibility in adapting to specific business needs.

**Visualization:**
Generated plots to visualize cluster distribution and highlight chosen distribution center locations based on density and distance considerations.

**Conclusion:**
By leveraging K-Means clustering and density-based analysis, the project successfully identified strategic distribution center locations. The variable parameter N provided flexibility for adapting to diverse business requirements, ensuring effective supply chain management and meeting customer demands efficiently.
