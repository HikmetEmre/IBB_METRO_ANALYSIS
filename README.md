# IBB_METRO_ANALYSIS
AN Exploratory Data Analysis Of Metro Istanbul
Perhaps, you didn’t hear yet but Istanbul Municipality has a Dataset platform! It has many datasets in very different categories.
I took the data from IBB Dataset Platform
Mostly datasets are storage as csv or xlsx files. For this project my data source was a PDF file. So, my first duty is converting PDF file to Pandas DataFrame.
Dataset source is “https://www.metro.istanbul/yolcuhizmetleri/yolcuistatistikleri”
With the help of Tabula Library we took the tables inside of PDF file and stored as List. Every element of this list equals to one year’s table.
For reading "PDF'S" AS "CSV" visit https://pypi.org/project/tableau/
