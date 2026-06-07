SELECT TOP (1000) [Customer_ID]
      ,[Age]
      ,[Gender]
      ,[Item_Purchased]
      ,[Category]
      ,[Purchase_Amount_USD]
      ,[Location]
      ,[Size]
      ,[Color]
      ,[Season]
      ,[Review_Rating]
      ,[Subscription_Status]
      ,[Payment_Method]
      ,[Shipping_Type]
      ,[Discount_Applied]
      ,[Promo_Code_Used]
      ,[Previous_Purchases]
      ,[Preferred_Payment_Method]
      ,[Frequency_of_Purchases]
  FROM [instant].[dbo].[shopping_trends]


use instant
-- Step 1: Data Overview

-- 1.1 Select sample data
SELECT TOP (10) * FROM shopping_trends;

-- 1.2 Count total rows
SELECT COUNT(*) AS Total_Rows FROM shopping_trends;   --3900

-- 1.3 Count total columns
SELECT COUNT(*) AS Total_Columns 
FROM information_schema.columns 
WHERE table_name = 'shopping_trends';                 --19

-- 1.4 Retrieve column names
SELECT COLUMN_NAME 
FROM INFORMATION_SCHEMA.COLUMNS 
WHERE TABLE_NAME = 'shopping_trends';

-- 1.5 table structure information
--metadata about table
SELECT 
    COLUMN_NAME,
    DATA_TYPE,
    CHARACTER_MAXIMUM_LENGTH AS Max_Length,
    IS_NULLABLE
FROM 
    INFORMATION_SCHEMA.COLUMNS
WHERE 
    TABLE_NAME = 'shopping_trends';