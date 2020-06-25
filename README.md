#The test is to perform a python based ETL task and present the solution along with the output.
#The data needs to be extracted from https://sec-api.io – it has a free tier that can be used for the
#purpose of this test. The API also has sandbox environment and documentation section. There are
#various reports available, however for the scope of this test we are only looking at Form D limited to
#filings in June 2020.
#We are looking specifically for companies incorporated in 2020 that belongs to any type of Pooled
#Investment Fund (Industry Group) except Other Investment Fund.
#The final data should have the following columns: CIK, Company Name, Filing Details URL, Entity
#Type, Principal Place of Business (City), and Pooled Investment Fund Type. The column list contains
#columns that are directly returned from the API and those that can be extracted from the filing
#document.
#In summary, the Python based script should extract data from the API and apply the transformations
#necessary to prepare and save the final data in the required format.
