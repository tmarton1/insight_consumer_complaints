# insight_consumer_complaints
Insight Data Engineering Coding Challenge

Place a complaints.csv file into the input directory.  Results will be written to the output directory as a report.csv file.

The complaints.csv input file must be formated as a series of comma-delimited lines with the following headings 
1.Date received
2.Product
3.Sub-product
4.Issue
5.Sub-issue
6.Consumer complaint narrative
7.Company public response
8.Company
9.State
10.ZIP code
11.Tags
12.Consumer consent provided?
13.Submitted via
14.Date sent to Company
15.Company response to consumer
16.Timely response?
17.Consumer disputed?
18.Complaint ID

Each row of the report.csv output file indicates
1.Product
2.Year
3.Total complaints for product-year combination
4.Total distinct companies receiving complaints for product-year combination
5.Highest percentage of total product-year complaints filed against the company, rounded to the nearest whole percent
