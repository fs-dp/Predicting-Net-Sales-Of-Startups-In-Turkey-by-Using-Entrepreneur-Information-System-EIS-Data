# Predicting-Net-Sales-Of-Startups-In-Turkey-by-Using-Entrepreneur-Information-System-EIS-Data

Entrepreneur Information System (EIS) of Turkey; is the project of collecting the data on the economic activities of the enterprises in the administrative records of different public institutions and organizations in a database within the framework of common standards and the integration of these data.


The main purpose of EIS, which was created within this framework, is to provide policy makers, decision makers, experts and researchers in public institutions and organizations, universities, research institutes and non-governmental organizations to design and implement economic, sectoral and regional policies and to measure efficiency at macro and micro level. It provides an environment where reliable and satisfying data/information will be presented.

In addition to the analyzes made at the macro level with EIS, studies with micro data can also be conducted. Thanks to the inter-institutional data integration carried out, data sets such as the financial statements of more than 3 million enterprises that generate commercial gains in the economy, their inter-sectoral and inter-provincial trade, Research and Small Business supports, intellectual and industrial rights, foreign trade and employment data can be accessed. In addition, data sets belonging to different institutions can be reported by cross-examination in EIS. For example, data such as employment of exporting companies, profit/loss status or financial performance of patented companies can be accessed.

The purpose of project is predicting net sales of companies based on the variables obtained from the database. Since the database is only open to certain individuals, permission is granted only for a portion of 2017 data. Accordingly,

  1)  A sample was taken from the 2017 EIS data within the scope of the project. Large enterprises and enterprises with zero total resources, net sales, marketing and distribution expenses and R&D expenditures were excluded when creating the sample data set. Therefore, the sample set is not representative of any real population.

  2) There are a total of 24 variables in the sample data, Initially, 11 of the selected variables is planned to be used in the regression model.
  
  3) Among selected variables, 'size', 'R&DCenter', and 'DesignCenter' data is categorical, the remaining 8 data (“total_assets”, “Equity”, “NetSales”, “R&D_Expenses”, “MarketingDistributionExpenses”, “Profit_Loss”, “Small_Business_Support” , “Research_Support”) is numerical data.
