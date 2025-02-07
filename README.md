# Electric-Vehicles-Market-Segmentation

## Project Overview
This project focuses on segmenting the Electric Vehicle (EV) market to identify the most optimal customer base. By leveraging data analysis and machine learning techniques, we aim to determine:
- The type of EVs a company should provide (e.g., bikes, scooters, trucks, cars).
- The ideal target customers based on demographics, profession, income, and geography.

## Dataset Information
The analysis is based on five datasets:

1. **EV_dataset.csv**
   - Columns: Year, Month_Name, Date, State, Vehicle_Class, Vehicle_Category, Vehicle_Type, EV_Sales_Quantity

2. **2-Wheeler.csv**
   - Columns: Used it for, Owned for, Ridden for, Rating, Visual Appeal, Reliability, Performance, Service Experience, Extra Features, Comfort, Maintenance cost, Value for Money, Model Name, Review.

3. **demographicData.csv**
   - Columns: Age, Profession, Marital Status, Education, Number of Dependents, Personal Loan, House Loan, Wife Working, Salary, Wife Salary, Total Salary, Make, Price.

4. **EV-Maker-by-Place.csv**
   - Columns: EV Maker, Place, State.

5. **final_dataset.csv**
   - Columns: S.No, State Name, Two Wheeler, Three Wheeler, Four Wheeler, Goods Vehicles, Public Service Vehicle, Special Category Vehicles, Ambulance/Hearses, Construction Equipment Vehicle, Other, Grand Total, Total Charging Stations.

## Project Workflow

### 1. Data Pre-processing
- Libraries Used: `pandas`, `numpy`, `matplotlib`, `seaborn`
- Handling missing values, cleaning text, and transforming categorical variables for analysis.

### 2. Segment Extraction
- Machine Learning Techniques: `K-Means Clustering` for identifying customer groups based on preferences, purchasing power, and needs.
- Principal Component Analysis (PCA) for dimensionality reduction and better visualization.

### 3. Profiling and Describing Potential Segments
- Grouped customers based on demographics and usage behavior.
- Identified key characteristics and preferences of each segment.

### 4. Selection of Target Segment
- Evaluated segments based on market size, purchasing power, and product alignment.
- Selected the most viable customer group for business strategy.

### 5. Customizing the Marketing Mix
- **Product:** Tailored vehicle features for the selected segment.
- **Price:** Determined an optimal pricing strategy.
- **Place:** Identified ideal locations for sales and distribution.
- **Promotion:** Designed marketing strategies targeting the selected customer base.

### 6. Potential Customer Base & Profit Estimation
- Estimated the early market potential.
- Used the formula: `Potential Customer Base * Target Price Range = Potential Profit`.

### 7. Market Entry Strategy
- Identified the most optimal market segments to target based on segmentation analysis.
- Recommended data-driven business strategies for EV adoption.

## Results & Insights
- The segmentation process highlighted key customer groups interested in two-wheelers and electric cars.
- Urban professionals and environmentally conscious consumers emerged as strong potential buyers.
- Insights were used to refine marketing and business strategies for maximum profitability.

## Conclusion
This project successfully segments the EV market, helping businesses identify and target the most promising customer groups. The insights derived can guide companies in product development, pricing, and marketing strategies for higher adoption and profitability.
