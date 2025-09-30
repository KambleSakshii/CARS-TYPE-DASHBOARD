# CARS-TYPE-DASHBOARD (EXCEL)
# 🚗 Cars Dashboard

A dynamic and interactive Excel dashboard for visualizing and analyzing car data, providing key insights into car specifications, performance, and risk factors.

## 🌟 Overview

This dashboard is designed to help users quickly understand trends and relationships within a dataset of car information. It uses various charts and metrics to present complex data in an easily digestible format.

## ✨ Key Features

* **Dynamic Filtering:** Utilize **Slicers** and **form controls (e.g., dropdowns/spinners)** to filter the data instantly based on criteria like `engine-type`, `make`, `fuel-type`, and `body-style`. *(Note: The image shows filter/slicer-like boxes in the top right.)*
* **Key Performance Indicators (KPIs):** Instant display of critical metrics:
    * Total Cars
    * Average Price
    * Average Horsepower (HP)
    * Maximum Price
* **Visual Data Analysis:** Includes multiple interactive charts:
    * **Pie Charts:** Displaying `SUM OF RISK-RATE VS DRIVE-WHEELS` and `COUNT OF CARS VS BODY STYLE`.
    * **Line/Area Chart:** Showing the relationship between `CITY MPG VS HIGHWAY MPG`.
    * **Bar/Column Charts:** Illustrating `Risk Rating vs Price`, `AVG HP BASED ON FUEL TYPE AND ENGINE TYPE`, and others.
    * **Doughnut Chart:** Visualizing `AVG PRICE VS BODY-STYLE`.
* **Segmented Views:** Separate sheets organize data based on different analytical focuses (as seen in the sheet tabs):
    * `1 RISK RATE VS DRIVE-WHEEL`
    * `2 CITY MPG VS HIGHWAY MPG`
    * `3 COUNT OF CARS VS BODY STYLE`

## 📊 Data Source

The dashboard is built upon a dataset containing various attributes for cars, including:

* Price
* Horsepower (HP)
* Fuel type (e.g., diesel, gas)
* Engine type
* Drive wheels (e.g., rear, front, 4wd)
* Body style (e.g., convertible, hardtop, sedan)
* MPG (City and Highway)
* Risk Rating (presumably calculated based on accident data/insurance risk)

## 🛠️ Requirements

To view and interact with this dashboard, you will need:

* **Microsoft Excel (2010 or newer)** or a compatible spreadsheet application (e.g., WPS Office, as seen in the screenshot) that fully supports Excel formulas, charts, and Slicers.

## 🚀 How to Use

1.  **Download:** Clone this repository or download the `cars_dashboard.xlsx` file.
2.  **Open:** Open the file in Microsoft Excel or compatible software.
3.  **Navigate:** Go to the **`DASHBOARD`** sheet.
4.  **Interact:** Use the **Filter boxes** on the right (e.g., `engine-type`, `make`) to instantly update all charts and KPIs based on your selections.
5.  **Explore:** Navigate to other tabs to view the underlying pivot tables or supporting data used to generate the dashboard.

## 🛑 Limitations

* The data is static and reflects the dataset at the time of creation. It will not automatically update with real-time car data.
* **Slicer/Filter** functionality may be limited or absent if opened in a non-Microsoft Excel program.

## 🤝 Contributing

This project is primarily a demonstration of data visualization and reporting in Excel. While direct code contributions aren't applicable, suggestions for improving the visualizations or adding new analytical views are welcome! Please open an issue to discuss.

## 📄 License

This project is for informational and educational purposes only.
