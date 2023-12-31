# Source Data:
![image](https://github.com/MohamedWageh09/BikeStores-Data-Mart-to-Dashboard-Development/assets/120044385/f0b99292-8a17-482b-ae2e-b14368798255)


# Data mart designing and creation

### Moved the data (flat files) to a staging DB:

![image](https://github.com/MohamedWageh09/BikeStores-Data-Mart-to-Dashboard-Development/assets/120044385/6a3632d3-b513-4b28-8a5d-df816f49904e)



### Created a dimentional model for the data mart:

![Model](https://github.com/MohamedWageh09/BikeStores-Data-Mart-to-Dashboard-Development/assets/120044385/3a04a6a1-5cf6-43e9-90dc-dbd859a5a118)

- Assumed that Customers and Products both are slowly changing dimensions type 2 


### Created the data mart DB and dimensions tables:

![image](https://github.com/MohamedWageh09/BikeStores-Data-Mart-to-Dashboard-Development/assets/120044385/71d781cd-52ed-4908-bd52-888e4968ad7c)

# ETL

### Customer Dimension Mapping:

![image](https://github.com/MohamedWageh09/BikeStores-Data-Mart-to-Dashboard-Development/assets/120044385/b393ebf7-a1fa-4411-b4d0-18f47e82b2bd)

### Staff Dimension Mapping:

![image](https://github.com/MohamedWageh09/BikeStores-Data-Mart-to-Dashboard-Development/assets/120044385/20ba775a-e498-4061-acf5-397806424b60)

### Product Dimension Mapping:

![image](https://github.com/MohamedWageh09/BikeStores-Data-Mart-to-Dashboard-Development/assets/120044385/514e17ff-d72b-462a-ba97-486727ac938f)

### Store Dimension Mapping:

![image](https://github.com/MohamedWageh09/BikeStores-Data-Mart-to-Dashboard-Development/assets/120044385/d2b74dd3-eb40-4ccd-bd0d-7620f9079eaf)

### Dim Date:

Used PL/SQL to populate the date dim

### Fact Mapping:

![image](https://github.com/MohamedWageh09/BikeStores-Data-Mart-to-Dashboard-Development/assets/120044385/238017b8-f351-4911-9ca4-ad664ff2758a)

### Workflow:

![image](https://github.com/MohamedWageh09/BikeStores-Data-Mart-to-Dashboard-Development/assets/120044385/1b991528-0825-4806-9882-43d5f130e5a6)

### Final Fact Table:

![image](https://github.com/MohamedWageh09/BikeStores-Data-Mart-to-Dashboard-Development/assets/120044385/7583c3de-e3e7-42a2-8173-c9daf4c5963c)

### Then Connected Power BI with the data mart and created the report:

![image](https://github.com/MohamedWageh09/BikeStores-Data-Mart-to-Dashboard-Development/assets/120044385/3411ad03-3917-4e8b-b711-555102729e78)








