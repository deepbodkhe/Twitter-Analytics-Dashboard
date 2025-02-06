# **Real-Time Twitter Analytics Dashboard - Power BI**

## **Overview**
This project focuses on building a **real-time Twitter analytics dashboard** using **Power BI** to analyze Twitter engagement metrics effectively. The dashboard provides interactive and time-sensitive insights into tweet impressions, engagement rates, and media interactions, ensuring a data-driven approach to social media analysis.

## **Features**
- **Real-Time Insights**: Track Twitter engagement in an interactive dashboard.
- **Time-Based Filtering**: Graphs appear based on predefined time slots.
- **Advanced Data Filtering**: Tweets filtered by impressions, likes, engagement rate, and word count.
- **Power BI Integration**: Uses **DAX and Power Query** for data transformation.
- **Customizable Visualizations**: Supports scatter plots, line charts, and trend analysis.

## **Key Visualizations**
1. **Engagement & Impressions Analysis** (3 PM – 5 PM IST)
   - Displays **average engagement rate and total impressions**.
   - Filters out tweets with **less than 100 impressions and zero likes**.
   - **Graph Placeholder** *(Insert Graph Here)*

2. **Media Engagement vs. Views** (6 PM – 11 PM IST)
   - Analyzes **media engagements vs. media views**.
   - Highlights tweets with **over 10 replies and engagement rate above 5%**.
   - **Filters**: Tweet date must be odd, word count above 50.
   - **Graph Placeholder** *(Insert Graph Here)*

3. **Engagement Rate Trend Analysis** (7 AM – 11 AM & 3 PM – 5 PM IST)
   - Displays **monthly engagement trends**.
   - Separates tweets **with and without media content**.
   - **Filters**: Even engagement numbers, odd tweet dates, character count above 20, and words excluding ‘C’.
   - **Graph Placeholder** *(Insert Graph Here)*

## **Technologies Used**
- **Power BI**: Data visualization and dashboard creation.
- **DAX & Power Query**: Data transformation and filtering.
- **Twitter Data Analysis**: Understanding user engagement trends.

## **Challenges & Solutions**
- **Challenge**: Implementing time-sensitive graphs.
  - **Solution**: Used DAX logic to restrict graph visibility within set time slots.
- **Challenge**: Filtering tweets dynamically based on multiple conditions.
  - **Solution**: Leveraged Power Query for preprocessing and DAX for runtime filtering.
- **Challenge**: Optimizing large datasets.
  - **Solution**: Indexed data and optimized Power BI models for better performance.

## **Project Outcomes**
- Developed a **fully functional Twitter analytics dashboard**.
- Gained hands-on experience in **Power BI, DAX, and Power Query**.
- Successfully implemented **time-sensitive visualizations** for real-time insights.

## **How to Use the Dashboard**
1. **Load the Power BI File**: Open the `.pbix` file in Power BI.
2. **Connect to Data Source**: Ensure the dataset is properly loaded.
3. **Interact with Visuals**: Explore different insights based on predefined time slots.
4. **Customize Filters**: Modify filters based on user requirements.

## **Repository and Files**
Find all project files, datasets, and Power BI reports in the GitHub repository:
[GitHub Repository](https://github.com/deepbodkhe/Twitter-Analytics-Dashboard)

## **Contact**
For any queries or contributions, feel free to reach out via GitHub.

