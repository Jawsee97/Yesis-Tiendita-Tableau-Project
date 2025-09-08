# 🏡 Yesi's Tiendita Tableau Project
## 📚 Background

My family owns a small business in the heart of my hometown of Santa Ana, CA with a HORRIBLE SECRET, they had little to NO data 😱 In the midst of preparing to ask around the community for free data consulting, I had a conversation with my mom that sparked my interest into getting to know what is REALLY going on in my families small business, surely they have to be doing something right since they have been open since 2020 right ? 😅

This Tableau Viz was comprised from my families small business dataset containing a csv table with 6,626 sales records from Jan 2024 - Aug 2025. (This was as much data I could gather within the month I was doing this project)

## 💡 Highlights

- Implemented the use of slicers for added timeline filtering
- Quantity of sales hit almost 10,000 in 2024 v.s. 5,863 in 2025 
- Profit margines are predicted to go down by 6%, projected by calcualting profit loss between Jan-Aug 2024 through Jan-Aug 2025
- Top Products were flowers, most notiably Roses and Sunflowers revenue hitting +$24k on the months of February, and May (Most likely due to Valentine's day and Mothers Day)
- Underpreforming products were notiably Baby Bottles along with Shampoo's and Conditioners hitting low revenue margins of $2k

## ✏️ Data Wrangling

Conducted simple data wrangling and data cleaning:
- Removed rows with missing values
- Cleaned the incosistent data formats of the `PURCHASE_DATE` column by using '=DATE(YEAR(C2),MONTH(C2),DAY(C2))'
- Cleaned the incosistent spelling of the `PRODUCT_NAME` column by using '=IF(C2="T shirt","T-shirt",C2)'
- Replaced "blank" rows with "Unknown" in the `CUSTOMER_ID` column by using '=IF(A2="","unknown",A2)'

📍 Tableau [Dashboard](https://public.tableau.com/views/YesisTienditaFinalDashboard/YesisTiendita?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## 📊 Visualization


Dashboard <img width="1337" height="899" alt="sales_dashboard" src="https://github.com/user-attachments/assets/cb5763a2-1b77-4634-a39c-5c6df82fe389" />

###
