# Meta Ads Data Fetch and Reporting via API

This script automates the process of fetching advertising data from the Meta Ads API, processing key metrics like revenue, spend, clicks, and ROAS (Return on Ad Spend), and writing the results to Google Sheets. The script supports daily data breakdowns and handles pagination for large datasets.

## Features
- Fetches daily Meta Ads data, including:
  - **Cost** (Spend)
  - **Revenue**
  - **Clicks**
  - **Purchases**
  - **CTR (Click-Through Rate)**
  - **CPC (Cost Per Click)**
  - **ROAS (Return on Ad Spend)**
- Automatically writes the data to a specified Google Sheets worksheet.
- Handles pagination and large data volumes.
- Includes error handling for API requests and Google Sheets integration.

## Technologies Used
- **Python**: For scripting and processing data.
- **Meta Ads API (Graph API)**: To fetch advertising data.
- **Google Sheets API (gspread)**: To update reports in Google Sheets.
- **Google Cloud Functions**: For automating the script execution via Pub/Sub.

## Prerequisites
1. **Python 3.9+**: 
2. **Meta Ads API Credentials**:
   
3. **Google Sheets API Credentials**:
   
4. **Google Cloud Functions Setup** (Optional):
   - Deploy the script and trigger it via Pub/Sub.


