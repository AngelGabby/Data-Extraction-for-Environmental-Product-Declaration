# Data Extraction for Environmental Product Declaration

## Project Overview
The Environmental Product Declaration (EPD) project aimed to extract valuable information from a dataset containing product descriptions with a focus on environmental impact. Postman was used in scrapping all the existing EPDs valid till 2023, using ECO Platform API. Out of 6820 EPDs valid till 2023, 100 EPDs were randomly selected.
One major challenge encountered during the project execution was that most documents were not in a consistent format. This was resolved by carefully evaluating each of the documents. 

## Clear Summary of the Task
The overarching goal of the data extraction process is to compile and analyze information from EPDs to provide stakeholders with comprehensive insights into the environmental performance of products.

## Parameters in Data Extraction
EPD Code, Group, EPD owner, EPD Programme Operator, Product Name, Registration No, Data Type,	Product Information, Product Category, Valid From, Valid To,	Geographical Representativeness, Temporal Representativeness, Standard Considered, Product Category Rules, Functional Unit, Declared unit, LCA database, LCA software, Global warming potential total (GWP-total)/ Climate change (kg CO2-eq), Global warming potential fossil fuels (GWP-fossil)/ Climate change (kg CO2-eq),	Global warming potential biogenic (GWP-biogenic)/ Climate change (kg CO2-eq), Global warming potential land use and land use change (GWP-luluc) / Climate change (kg CO2-eq), Ozone layer depletion / Stratospheric ozone depletion (kg CFC-11-eq), Acidification potential (mol H+ eq), Eutrophication aquatic freshwater (kg P eq),Eutrophication aquatic marine (kg N eq), Eutrophication aquatic terrestrial (mol N eq), Eutrophication Potential according to ISO 21930-2017 (kg PO4 3-eq), Photochemical ozone formation (kg NMVOC eq), Depletion of abiotic resources - mineral and metals (kg Sb eq), Depletion of abiotic resources - fossil fuels (MJ), Water use (m3-eq), Particulate matter emissions (Disease incidence), Ionizing radiation human health (kBq U235 eq), Eco-toxicity (freshwater) (CTUe),	Human toxicity, cancer (CTUh),	Human toxicity, non-cancer effects (CTUh), Soil Quality(Pt), Use of renewable primary energy excluding renewable primary energy resources used as raw materials (MJ), Use of renewable primary energy resources used as raw materials (MJ), Total use of renewable primary energy resources (primary energy and primary energy resources used as raw materials (MJ), Use of non-renewable primary energy excluding renewable primary energy resources used as raw materials (MJ),	Use of non-renewable primary energy resources used as raw materials (MJ), Total use of non-renewable primary energy resources (primary energy and primary energy resources used as raw materials (MJ),	Use of secondary material (kg), Use of renewable secondary fuels (MJ),	Use of non-renewable secondary fuels (MJ), Recovered energy (MJ), Consumption of fresh water  (m3), Net use of fresh water  (m3), Hazardous waste disposed (kg), Non-hazardous waste disposed (kg), Radioactive waste disposed (kg), Components for re-use (kg), Materials for recycling (kg), Materials for energy recovery (kg),  Exported Energy (MJ), Biogenic removals and emissions within bio-based products (kg CO2 eq. (100 years), Biogenic removals and emissions within packaging (kg CO2 eq. (100 years), Biogenic carbon content in product (kg C)	, Biogenic carbon content in accompanying packaging (kg C), Removals and emissions from calcination and carbonation - ISO21930 (kg CO2 eq. (100 years), Biogenic CO2 (combustion of waste) - ISO21930 (kg CO2 eq. (100 years), Biogenic CO2 (leaving the product system) - ISO21930 (kg CO2 eq. (100 years)

## Data Preprocessing
Cleaned the collected data by removing duplicates, irrelevant information, and addressing inconsistencies to ensure the integrity of extracted information. This ensured that the extracted data accurately reflects the environmental attributes of products as reported in EPDs.

## Manual Data Extraction to Microsoft Excel Spreadsheet
One hundred EPDs were selected for further extraction. A template was designed for data extraction using the parameters stated to be considered. Populated the template with data from the EPDs document using the data quality assurance metrics.

## Analysis
Frequency distribution including percentage was used to analyze the data.

**Total Number of EPDs on ECO Platform and Programme Operator**

![image](https://github.com/AngelGabby/Data-Extraction-for-Environmental-Product-Declaration/assets/34291140/1d951c5c-7e2d-4c6a-adc4-70522125e967)

**Manufacturers and Number of EPDs in the 100 Sample**

![image](https://github.com/AngelGabby/Data-Extraction-for-Environmental-Product-Declaration/assets/34291140/85aa0664-38d9-4866-a28a-ee6c16fbc54e)

## Data Visualization
Visualize the extracted information using charts, graphs, and other visualization techniques to provide insights into the EPDs' data quality assurance levels.

**Number of EPDs and Owners**

![image](https://github.com/AngelGabby/Data-Extraction-for-Environmental-Product-Declaration/assets/34291140/7c7d244b-35d2-44d9-961b-d9d0fdfaf4d9)


**Functional Unit**

![image](https://github.com/AngelGabby/Data-Extraction-for-Environmental-Product-Declaration/assets/34291140/8420cb2e-d510-4d42-9cce-8dbfbce449ef)


**Geographical Representativeness**

![image](https://github.com/AngelGabby/Data-Extraction-for-Environmental-Product-Declaration/assets/34291140/01f79180-029f-4870-b2ab-6b09730b5a7b)



## Conclusions and Recommendations

1. **Data Quality is Key**: High-quality data within EPDs is essential for accurately assessing the environmental performance of products. Ensuring that EPDs contain reliable and consistent data on environmental impacts such as carbon emissions and resource consumption is crucial for meaningful analysis and decision-making.

2. **Robust Preprocessing is Essential**: Preprocessing EPD data involves standardizing units, handling missing values, and addressing inconsistencies to ensure the integrity of extracted information. Robust preprocessing ensures that the extracted data accurately reflects the environmental attributes of products as reported in EPDs.

3. **Domain Knowledge is Valuable**: Understanding the environmental terminology, life cycle assessment methodologies, and regulatory frameworks underlying EPDs is critical for effective data extraction. Domain knowledge enables informed preprocessing decisions and facilitates the interpretation of extracted environmental metrics.

4. **Iterative Approach Yields Better Results**: Iteratively refining data extraction techniques based on feedback and validation improves the accuracy and relevance of extracted environmental data. Iterative cycles of extraction and analysis enable the identification and correction of errors or discrepancies in EPD data.

5. **Flexibility in Tool Selection**: EPDs may vary in format and structure, necessitating flexibility in tool selection for data extraction. Utilizing a diverse toolkit of extraction methods and software enables adaptation to different EPD formats and enhances the efficiency of data extraction processes.



