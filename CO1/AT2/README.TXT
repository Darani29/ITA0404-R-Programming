ITA0404  Statistics with R programming
ASSESSMENT TOOL 2 
1. Employee Salary Processing
o Write a pseudocode to: 
 Create a data frame with Employee ID, Name, Department, and Salary. 
 Create a logical vector to identify employees earning more than 
₹50,000. 
 Store the filtered employee details in a list. 
 Display the number of eligible employees. 
Answer
Pseudocode:
    • START
    • Create a data frame Employee_Data with columns:
                                                         Employee_ID = vector of employee IDs
                                                         Name = character vector of employee names
                                                         Department = character vector of departments
                                                         Salary = numeric vector of salaries
    • Create a logical vector:
                                                         Eligible = Salary > 50000
    • Filter employee details where Eligible is TRUE
    • Store filtered employee details in a list:
                                                           Eligible_Employees = list(Employee_Data[Eligible, ])
    •  Display number of eligible employees:
                                                           Count = length(Employee_Data[Eligible, ])

    • Print Count
    • STOP
2. Inventory Management
o Write a pseudocode to: 
 Create a data frame containing Item Name, Quantity, and Unit Price. 
 Calculate the total value of each item. 
 Generate a logical vector to identify items with stock below the 
minimum level. 
 Store the low-stock items in a list and display them. 
Answer
pseudocode:
    • START
    • Create a data frame Inventory_Data with columns:
                                        Item_Name = character vector of item names
                                       Quantity = numeric vector of available stock
                                        Unit_Price = numeric vector of item prices
    • Calculate total value of each item:
                                         Total_Value = Quantity * Unit_Price
    • Add Total_Value column to Inventory_Data
    • Define minimum stock level
    • Create logical vector:
                                        Low_Stock = Quantity < Minimum_Level
    • Filter items where Low_Stock is TRUE
    • Store low-stock details in a list:
                                       Low_Stock_Items = list(Inventory_Data[Low_Stock, ])
    • Display Low_Stock_Items
    • STOP
3. Examination Result Processing
o Write a pseudocode to: 
 Create vectors for student names and marks. 
 Define a function to assign grades based on marks. 
 Store the grades as a factor. 
 Create a data frame containing Name, Marks, and Grade. 
 Display the number of students in each grade category. 
Answer
pseudocode:
    • START
    • Create a data frame Inventory_Data with columns:
                                      Item_Name = character vector of item names
                                      Quantity = numeric vector of available stock
                                      Unit_Price = numeric vector of item prices
    • Calculate total value of each item:
                                        Total_Value = Quantity * Unit_Price
    •  Add Total_Value column to Inventory_Data
    • Define minimum stock level
    • Create logical vector:
                                         Low_Stock = Quantity < Minimum_Level
    • Filter items where Low_Stock is TRUE
    • Store low-stock details in a list:
                                       Low_Stock_Items = list(Inventory_Data[Low_Stock, ])
    • Display Low_Stock_Items
    • STOP
4. Weather Data Processing
o Write a pseudocode to: 
 Create vectors for daily temperatures. 
 Generate a logical vector identifying days with temperatures above 
35°C. 
 Count the number of hot days. 
 Store the results in a list and display them. 
Answer
pseudocode:
    • START
    • Create numeric vector:
                          Temperature = daily temperature values
    • Create logical vector:
                           Hot_Days = Temperature > 35
    • Count number of hot days:
                          Hot_Day_Count = sum(Hot_Days)
    • Create a list to store results:
                         Weather_Result = list(
                         Temperatures = Temperature,
                         Hot_Day_Status = Hot_Days,
                         Number_of_Hot_Days = Hot_Day_Count)
    •    Display Weather_Result
    • STOP
5. Library Book Analysis
o Write a pseudocode to: 
 Create a data frame containing Book ID, Title, and Number of Copies. 
 Generate a logical vector to identify books with fewer than five copies. 
 Store the book titles in a character vector. 
 Display the list of books requiring replenishment. 
Answer
pseudocode:
    • START
    • Create a data frame Library_Data with columns:
                                      Book_ID = vector of book IDs
                                      Title = character vector of book titles
                                     Copies = numeric vector of available copies
    • Create logical vector:
                                     Replenish_Needed = Copies < 5
    • Extract titles of books requiring replenishment:
                                     Replenishment_Books = Title[Replenish_Needed]
    • Store book titles in character vector:
                                      Book_List = character vector of Replenishment_Books
    • Display Book_List
    • STOP
