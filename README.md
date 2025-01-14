                                       **Capstone Project on Monitor Sales Report**
                                       
**Business**
    o The data consists of sales report from a leading Monitor Distributor in Kerala.
    o They are primarily the distributors of a Taiwanese multinational company that sells and markets technology products, consumer electronics, computing and communications devices.
    o The fiscal year in Taiwan runs from January to December. The same format is followed in the analysis.
    o The data considered is from January 2021 to December 2021.
    o The items are distributed to dealers and some of the individual customers.
    o This data is mainly used for below purposes.
      1. To send a weekly update on the sales to the management.
      2. To analyze the sales on various locations.
      
**Data Collection:**
      I have collected this data from my friend who is working as Area Sales Manager with a Distributor with the company at Cochin.  He had later mailed me the data via email. After an initial analysis, I discussed with him about their business and clarified some confusions about the data.
      The data is maintained in SAP .The data consists of the sellout report for the year 2021 across Kerala.
      
**Preprocessing to Cleanse the Data:**
      o Location - Most of the data was in uppercase whereas some of them where a mixture of upper and lower case letters. Updated all of them to upper case for convenience.
      o Date: Most of the dates where proper, but some of them where formatted as text and in a different form. All of them have been updated to mini date format eg: 29-12-          2021. Because of the invalid format many rows where excluded while doing a pivot or filter.
      o SKU: There were multiple spaces on both the sides of the SKU field data. It had been trimmed out using TRIM () function.
      o Month, Quarter: These fields where missing, populated them using Date field.
      
**Analysis**
      o Analysis is mainly focused on the volume, revenue, monthly, quarterly and location wise sales.
      o By analyzing this report,
           The most selling and revenue producing SKUs are identified.
           Monthly, Quarterly trends of sale is visualized
           Location and partner volume of sales is checked and identified the focus areas
      o Volume pareto, revenue pareto and Partner sale trend is visualized for top 20 items.
      
**Recommendations**
      o They can provide more free or combo offers during regional holidays or festive season like Onam.
      o Considering the current Covid imposed online work and study culture, a student or corporate purchase program can be introduced in the low sales locations.
      o 80% sales happens with high priced items in hypermarket and electronics store. Low priced items can be promoted via small shops to improve sales.
