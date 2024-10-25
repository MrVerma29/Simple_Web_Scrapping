# Web Scraping Project: Company Analysis Across Different Sectors

## Overview
This project involves web scraping to analyze three companies—Nestlé, Pfizer, and Coca-Cola—operating in different sectors (nutrition, pharmaceuticals, and beverages). The objective is to extract relevant data from their websites and organize it in an Excel file for further analysis.

## Libraries Used
- **Requests**: For sending HTTP requests to access the websites.
- **BeautifulSoup**: For parsing HTML content and extracting relevant data.
- **Pandas**: For creating and managing data structures, particularly DataFrames.
- **OpenPyXL**: For saving the DataFrame to an Excel file and applying formatting.

## Objectives
The project consists of the following objectives, with corresponding column names:

| Column Name            | Objective                                                                                      |
|------------------------|------------------------------------------------------------------------------------------------|
| Products Offered       | To check if the company offers relevant products such as nutrition items, supplements, etc.    |
| Company Description    | To gather information about the company's history, mission, and values.                        |             
| Category               | To identify the company's role (manufacturer, distributor, or brand) in its respective sector. |
| Manufacturer           | To verify the company's manufacturing processes and facilities.                                |
| Brand Presence         | To showcase the variety of brands and products the company offers.                             |
| Distribution Role      | To analyze the company's distribution strategies and supply chain involvement.                 |

## How It Works
1. **Web Scraping**: The script accesses each company's website and extracts relevant content based on defined CSS selectors.
2. **Keyword Matching**: It checks for specific keywords associated with each objective, determining whether they apply to the company.
3. **Data Organization**: The results are stored in a Pandas DataFrame for easy manipulation and analysis.
4. **Export to Excel**: The final DataFrame is exported to an Excel file located at `C:\Users\verma\Downloads`, with basic conditional formatting applied for better visual representation.

# Conclusion

This project demonstrates a practical application of web scraping techniques to gather and analyze data from multiple sectors. Through the process of extracting and organizing data, it illustrates how Python can be leveraged to automate the collection of information from web sources, making it easier to analyze and compare various companies. 

This project serves as a valuable resource for anyone interested in learning about:

- **Web Scraping:** Understanding how to programmatically retrieve data from websites.
- **Data Extraction:** Gaining insights into parsing HTML and locating specific data points.
- **Data Formatting:** Learning how to structure data for analysis and presentation using libraries like Pandas and OpenPyXL.

Overall, this project not only showcases the technical skills involved in web scraping but also emphasizes the importance of data in making informed business decisions across different sectors.
