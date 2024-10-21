# LITA_Class_Documentation

### Project Title : Data Literacy Project  
---
### project overview
---

This Data Analysis project aims to generate insight into the ability to read, write, analyze, communicate, and reason with data. It’s a skill that allows individuals and organizations to make better, data-driven decisions. As with other key competencies, it’s not a one-size-fits-all concept; multiple facets make up data literacy. It is more than just data analysis; instead, it involves understanding what data means and how to present those findings.

---
### Data Sources
The primary source of data used here are surveys, questionaires and interviews, these are some common sources data that can be freely downloaded from an open source online such as kaggle database or Google dataset search or any other data repository site.

---
### Store Data
1. cloud
2. premises 

---
### Tools used 
- miscrosoft Excel [Download Here](https://www.microsoft.com)
1.  For data cleaning
2.  For analysis
3.  For data visualization

---
### Data Cleaning And Preparation
A significant part of my role as a data analyst is cleaning data to prepare it for analysis. Data cleaning (also called data scrubbing) is the process of removing incorrect and duplicate data, managing any holes in the data, and ensuring consistent formatting. 

### These are common data cleaning in excel Task:
- Remove duplicates
-  Standardize formats
-  Even out casing and remove extra spaces
-  Split delimited data
-  Find and replace
-  Extract prefixes and suffixes
-  Check for spelling and typos
-  Fill missing values

---
### Exploratory data analysis (EDA)
Data analysis is all about answering questions with data. Exploratory data analysis, or EDA for short, helps me explore what questions to ask. This could be done separately from or in conjunction with data cleaning.

- Ask lots of questions about the data.
- Discover the underlying structure of the data.
- Look for trends, patterns, and anomalies in the data.
- Test hypotheses and validate assumptions about the data.
- Think about what problems you could potentially solve with the data.

### Skill requirements for data analysis 
- python
- R language
- SQL
- Tableau

  ### Technical skills / programming language
  - python
  - R language
  - SQL
 
 ### Data Visualization 
 - Tableau
 - Power BI

### Critical Thinking 

### Data wrangling and cleaning 

### communication skills 
-----
 ## Data visualization
Data virtualization provides a modern data layer that enables users to access, combine, transform, and deliver datasets with breakthrough speed and cost-effectiveness. Data virtualization technology gives users fast access to data housed throughout the enterprise—including in traditional databases, big data sources, and cloud and IoT systems—at a fraction of physical warehousing and extract/transform/load (ETL) time and cost.

![DATA VIRTUALIZATION](https://github.com/user-attachments/assets/766b3bb2-0b80-4532-b06e-77a832808131)

-------

### Common data sources virtualized through data virtualization software

![common data sources](https://github.com/user-attachments/assets/05a54a72-2a9f-4d71-b406-e29c0b6b2517)

Packaged apps
RDBMS
Excel & flat files
Data warehouses
Data lakes
Big data
XML docs
Cloud data
Web services
IoT data

## Functions to convert dirty data 
- lower : lower case 
- upper: Upper case 
- proper : Start with upper and end with lower
- To generate random data " Randbetween
- cobtrol 0 to hide data
- to get the first name : = left (
- to join first and surname : Concatenate, text join , = Left(cell number, find( " " )

## conditional data analysis formula 

### summation without conditions
- sum , average, max, counta ,

### With certain conditions 
- sumif, averageif , countif, maxif

### more than one criteria 
- sumifs, averageifs, countifs, maxifs

## Lookup functions in Excel: it help find specific data within a range or table. Here are the most commonly used lookup functions:

### VLOOKUP

Syntax: VLOOKUP(lookup_value, table_array, col_index_num, [range_lookup])

Example: =VLOOKUP(A2, B:C, 2, FALSE) looks up value in cell A2 in column B and returns corresponding value in column C.

### INDEX/MATCH

Syntax: INDEX(range, MATCH(lookup_value, range, [match_type])

Example: =INDEX(C:C, MATCH(A2, B:B, 0)) looks up value in cell A2 in column B and returns corresponding value in column C.

### HLOOKUP

Syntax: HLOOKUP(lookup_value, table_array, row_index_num, [range_lookup])

Example: =HLOOKUP(A2, B:C, 2, FALSE) looks up value in cell A2 in row B and returns corresponding value in row C.

### LOOKUP

Syntax: LOOKUP(lookup_value, table_array)

Example: =LOOKUP(A2, B:C) looks up value in cell A2 in column B and returns corresponding value in column C.

### Lookup Function Differences:

- VLOOKUP:
- Looks up values in a table.
- Returns a value from a specific column.
- Can return an approximate match.

  ### INDEX/MATCH:
  - More flexible and powerful.
  - Looks up values in a range or table.
 - Returns a value from any range.
    - Exact match only.

 ### HLOOKUP:
  - Looks up values in a table.
  - Returns a value from a specific row.
- Can return an approximate match.
  
### LOOKUP:
- Simple lookup function.
- Looks up values in a table.
- Returns a value from the same table.

### Tips and Best Practices:

- Use absolute references ($A$2) instead of relative references (A2).
- Use table references instead of range references.
- Avoid using VLOOKUP with large datasets.
- INDEX/MATCH is often faster and more efficient.
- Use LOOKUP for simple, exact matches.

### Common Errors:

- #N/A (value not found)
- #REF! (invalid reference)
- #VALUE! (invalid data type)

### Troubleshooting:

- Check spelling and formatting.
- Verify lookup value exists.
 - Adjust range or table references.

### what are the specific lookup question or scenario?

-  VLOOKUP issue
- INDEX/MATCH query
- HLOOKUP problem
- LOOKUP trouble
- Other (please specify)

### Here are the most commonly used lookup functions:

### VLOOKUP*

Syntax: VLOOKUP(lookup_value, table_array, col_index_num, [range_lookup])

Example: =VLOOKUP(A2, B:C, 2, FALSE) looks up value in cell A2 in column B and returns corresponding value in column C.

### INDEX/MATCH*

Syntax: INDEX(range, MATCH(lookup_value, range, [match_type])

Example: =INDEX(C:C, MATCH(A2, B:B, 0)) looks up value in cell A2 in column B and returns corresponding value in column C.

### HLOOKUP*

Syntax: HLOOKUP(lookup_value, table_array, row_index_num, [range_lookup])

Example: =HLOOKUP(A2, B:C, 2, FALSE) looks up value in cell A2 in row B and returns corresponding value in row C.

### LOOKUP*

Syntax: LOOKUP(lookup_value, table_array)

Example: =LOOKUP(A2, B:C) looks up value in cell A2 in column B and returns corresponding value in column C.

## Lookup Function Differences:

### VLOOKUP:
    - Looks up values in a table.
    - Returns a value from a specific column.
    - Can return an approximate match.
    
 ### INDEX/MATCH:
    - More flexible and powerful.
    - Looks up values in a range or table.
    - Returns a value from any range.
    - Exact match only.
### HLOOKUP:
    - Looks up values in a table.
    - Returns a value from a specific row.
    - Can return an approximate match.
    
 ### LOOKUP:
    - Simple lookup function.
    - Looks up values in a table.
    - Returns a value from the same table.

 
### Pivot Table 

This is the tool that summarize data. 
control shift 1 is to get decimal in data. 

### cell referencing 

This means how Excel treat whatever cell you are referencing in your calculation. 

# Kind of Cell Referencing 
- Relative : free to move
- Absolute: locking
- column constant: $u7
- Roll constant: U$7
The last two are mixed referencing.
= formulatex-to pull out the exact formula behind result.

### absolute =select salary* by percentage increase. 
- press f4 to lock cell etc 
