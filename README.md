# Super_Store_Sales_Data_Cleaning
Software used for task is **Power BI**
<br>
### Actions performed
- Checked for null values in the dataset
- Removed the column RowId as there was no need for it as there were 3 keys that are already present in the dataset - OrderId, CustomerId and ProductId
- Removed the column Country as the entire dataset is for United States
- Changed datatype of PostalCode from integer to text as I don't want any integer based operations to be performed on it by any chance
- Made all the headers of the table consistent and in same format
- Removed duplicate rows
