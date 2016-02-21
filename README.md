# Data-Warehouse-BI-
Architect, Populate and Explore a Data Warehouse for Business Intelligence

1	Introduction
ABC LTD is a famous UK wholesale company. This company sells goods to different Cash and Carry store all over UK. ABC LTD is interested in building new data warehouse for their company, to improve it’s corporate planning and report mechanism and address issues of competitive intelligence.
Two most commonly used approaches for building data warehouse introduced by Bill Inmon and Ralph Kimball are:
Bill Inmon’s enterprise data warehouse approach (the top-down design): A normalized data model is designed first. Then the dimensional data marts, which contain data required for specific business processes or specific departments are created from the data warehouse.
Ralph Kimball’s dimensional design approach (the bottom-up design): The data marts facilitating reports and analysis are created first; these are then combined together to create a broad data warehouse.
In my data warehouse implementation project I am following Kimball approach, as this is easy to implement , low cost , faster to build and easily scalable. This document summarises all the steps taken to implement data warehouse which gives 360 degree point of view of ABC business to it’s stakeholders, including the ETL process and Business intelligence reports drown from this data warehouse.
