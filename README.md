# A/B Test Analysis for Foodtech Company

## 📌 Overview
This project was conducted as part of the **Compety Hackathon**, where we analyzed an A/B test to determine whether increasing the size of food images on restaurant menu cards improves conversion rates. The dataset provided interaction logs from users across different platforms (iOS & Android) during the experiment.

## 🚀 Project Objectives
- **Evaluate the A/B test design** to ensure statistical validity.
- **Analyze the dataset** to extract insights about user behavior.
- **Draw conclusions and make business recommendations** for product improvements.

## 📝 Hackathon Task
The experiment tested the hypothesis:
> **Increasing the size of food images on restaurant menu cards will improve conversion rates.**

- **Test Location:** London
- **Duration:** 25th Nov 2024 - 30th Nov 2024
- **Key UI Difference:** 
  - **Control Group (1):** Small images
  - **Test Group (2):** Large images
- **Metrics Measured:** User interactions (page reloads, shop entries, order completions)

## 📊 Dataset
The dataset contains **326,921 rows** with key fields:
- `variation`: Identifies the control (1) and test (2) groups
- `platform`: Captures user platform (iOS or Android)
- `event_type`: Tracks user interactions (e.g., shop entry, order payment, order completion)
- `final_order_status`: Captures order outcomes
- `datetime_event`: Timestamp for each event

📌 **Dataset Link:** [Download Here](https://drive.google.com/drive/folders/1-w_AYmMctY2gleWY0A-Ez9LYBJbx7kHK)

## 🔍 Key Insights
- **User Engagement Analysis:**
  - This chart shows user interactions for different events in both variations.
  ![image](https://github.com/user-attachments/assets/6146e548-ec51-41d5-85d6-3b1044da854c)

- **Conversion Rate:**
  - **Control Group:** 42.41%
  - **Test Group:** 42.20%
  - No statistically significant impact from larger images.
  ![image](https://github.com/user-attachments/assets/ecf6b098-c15d-4947-94f6-2d3272283f55)

- **Platform-Based Segmentation:**
  - No major difference in conversion rates between **iOS** and **Android**.
<p align="center">
    <img src="https://github.com/user-attachments/assets/d03721aa-fc69-4fc4-8432-436f3a634341" height="200">
    <img src="https://github.com/user-attachments/assets/2a7cfe84-07d4-4832-adbf-a97ca7183041" height="200">
</p>

- **Day & Time Analysis:**
  - Order rates remained stable across different days of the week.
<p align="center">
    <img src="https://github.com/user-attachments/assets/4c089529-d0d5-45e1-b645-88bbe2ab6a81" height="200">
    <img src="https://github.com/user-attachments/assets/41cfaeff-06c7-4b07-9af2-caecfc5809ef" height="200">
</p>

  - This shows peak order hours for each variation.
<p align="center">
    <img src="https://github.com/user-attachments/assets/2fb0e23a-a292-479c-85f2-de1681f1d1ed" height="200">
    <img src="https://github.com/user-attachments/assets/3ed26c44-d913-4cb4-9b2f-c9d41450e630" height="200">
</p>

- **Refund Rates:**
  - Lower refund rates in the test group, suggesting a better post-purchase experience.
  ![image](https://github.com/user-attachments/assets/cac58f9d-4efb-4b98-b194-34bc6e56a6d8)

📌 **Full Analysis:** Check the [Jupyter Notebook](Analysis.ipynb) for detailed calculations.

## 📌 Business Recommendations
✅ Explore **other UX/UI changes** beyond image size, such as product descriptions or reviews.  
✅ Consider **bundling images** with ingredient lists and portion sizes.  
✅ Assess **profitability impact** beyond just conversion rates.  

## 🎥 Project Deliverables
- 📊 **[Presentation Slides](https://www.canva.com/design/DAGhgAx6Nvo/w4nP3bjfSGh8l3OZ7Nq00w/edit?utm_content=DAGhgAx6Nvo&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)**
- 🎥 **[Presentation Recording](https://www.loom.com/share/9dc43ae1c8884330b27196b541267ff4?sid=154a26bb-af90-433a-8d81-ff65be456eaa)**

## 🔗 References
- **Hackathon Host:** [Compety Hackathon](https://compety.net)
- **Submission Deadline:** 12th March 2025

## 🙌 Acknowledgements
Special thanks to the **Compety Hackathon team** for organizing this event and providing a great learning opportunity!
