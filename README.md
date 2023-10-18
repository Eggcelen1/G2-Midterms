<p align="center">
  <img src="https://github.com/Eggcelen1/G2-Midterms/assets/144224540/ce61609e-f78d-415c-80d2-6d3a8bf5146a">
</p>

-------------------------------------------------------------------------------------------------------------------------

<p align="center">
  <img src="https://github.com/Eggcelen1/G2-Midterms/assets/144224540/fae5aa34-1017-4f43-836d-4d7c006c34a3">
</p>


- ## LENGTH Function
    ☆ **LEN** returns the number of characters in a text string.

  - ### _Syntax_
        =LEN(text) 

<p align="center">
  <img src="https://github.com/Eggcelen1/G2-Midterms/assets/144224540/55ef0faa-5559-42b4-b7a7-7e01792931dc">
</p>


  - ## LOWER Function
    ☆ Converts all uppercase letters in a text string to lowercase.
    
    - ### _Syntax_
          =LOWER(text)

<p align="center">
  <img src="https://github.com/Eggcelen1/G2-Midterms/assets/144224540/a4468b60-6023-4927-a627-03b9079cdf99">
</p>


  - ## UPPER Function
    ☆ Converts text to uppercase
    
    - ### _Syntax_
          =UPPER(text)

<p align="center">
  <img src="https://github.com/Eggcelen1/G2-Midterms/assets/144224540/a1b6d9f8-9551-4c80-ab80-3583951bb4f2">
</p>

      
  - ## REPLACE Fumction
    ☆ **REPLACE** replaces part of a text string, based on the number of characters you specify, with a different text string
    
    - ### _Syntax_
          =REPLACE(old_text, start_num, num_chars, new_text)

<p align="center">
  <img src="https://github.com/Eggcelen1/G2-Midterms/assets/144224540/76b3d803-1d75-45b8-ab21-32789178cf0b">
</p>


  - ## CONCATENATE Function
    ☆ Use **CONCATENATE**, one of the text functions, to join two or more text strings into one string.

    - ### _Syntax_
          =CONCATENATE("Stream population for ", A2, " ", A3, " is ", A4, "/mile.")
    - ### _Syntax_
          =CONCATENATE(B2, " ",C2)

<p align="center">
  <img src="https://github.com/Eggcelen1/G2-Midterms/assets/144224540/34b5315d-b84f-4309-ac54-f44b658942bc">
</p>

-------------------------------------------------------------------------------------------------------------------------

<p align="center">
  <img src="https://github.com/Eggcelen1/G2-Midterms/assets/144224540/361eb32f-06b0-4834-9647-6376f135275a">
</p>

  - ## FLOOR function 
    ☆ Rounds number down, toward zero, to the nearest multiple of significance
    
    - ### _Syntax_
          =FLOOR(number, significance)
<p align="center">
  <img src="https://github.com/Eggcelen1/G2-Midterms/assets/144224540/473d3a96-0d4e-4f2c-a398-cbe3e640c087">
</p>

  - ## CEILING function       
    ☆ Returns number rounded up, away from zero, to the nearest multiple of significance. For example, if you want to avoid using pennies in your prices and your product is priced at $4.42, use the formula =CEILING(4.42,0.05) to round prices up to the nearest nickel.
    - ### _Syntax_
          =CEILING(number, significance)
<p align="center">
  <img src="https://github.com/Eggcelen1/G2-Midterms/assets/144224540/8ab4f4d1-c721-424b-9aa2-8b8d1955046d">
</p>

  - ## EVEN function       
    ☆ Returns number rounded up to the nearest even integer. You can use this function for processing items that come in twos. For example, a packing crate accepts rows of one or two items. The crate is full when the number of items, rounded up to the nearest two, matches the crate's capacity.

    - ### _Syntax_
          =EVEN(number)

<p align="center">
  <img src="https://github.com/Eggcelen1/G2-Midterms/assets/144224540/aed0a6b5-f6cc-4d24-9513-72216c257e2d">
</p>

  - ## ODD function       
    ☆ Returns number rounded up to the nearest odd integer
    
    - ### _Syntax_
          =ODD(number)
<p align="center">
  <img src="https://github.com/Eggcelen1/G2-Midterms/assets/144224540/0f090e31-c619-440a-96f3-fb21c32b4294">
</p>

  - ## TRUNC function       
    ☆ Truncates a number to an integer by removing the fractional part of the number.
    
    - ### _Syntax_
          =TRUNC(number, [num_digits])

<p align="center">
  <img src="https://github.com/Eggcelen1/G2-Midterms/assets/144224540/5513c48c-c80a-4d44-ae0e-02148d98df4a">
</p>

-------------------------------------------------------------------------------------------------------------------------

<p align="center">
  <img src="https://github.com/Eggcelen1/G2-Midterms/assets/144224540/facae50c-7021-47cf-9f8d-b9cdcea97654">
</p>

  - ## NOT function       
    ☆ Use the **NOT** function, one of the logical functions, when you want to make sure one value is not equal to another.
    
    - ### _Syntax_
          =NOT(A2>100)
    - ### _Syntax_
          =IF(AND(NOT(A2>1),NOT(A2<100)),A2,"The value is out of range")\
    - ### _Syntax_
          =IF(OR(NOT(A3<0),NOT(A3>50)),A3,"The value is out of range")
<p align="center">
  <img src="https://github.com/Eggcelen1/G2-Midterms/assets/144224540/a509e343-7ff9-4176-bf7a-4d50d8092d88">
</p>

  - ## IF function       
    ☆ The **IF** function is one of the most popular functions in Excel, and it allows you to make logical comparisons between a value and what you expect.

      So an IF statement can have two results. The first result is if your comparison is True, the second if your comparison is False.

      For example, =IF(C2=”Yes”,1,2) says IF(C2 = Yes, then return a 1, otherwise return a 2).
  
    
    - ### _Syntax_     
           =IF(A2>B2,"Over Budget","OK")
    - ### _Syntax_
          =IF(A2=B2,B4-A4,"")

<p align="center">
  <img src="https://github.com/Eggcelen1/G2-Midterms/assets/144224540/085ca92d-4d4d-4742-9b18-8426e5d50f89">
</p>

  - ## COUNTIF function
    ☆ Use **COUNTIF**, one of the statistical functions, to count the number of cells that meet a criterion; for example, to count the number of times a particular city appears in a customer list.

    - ### _Syntax_
          =COUNTIF(A2:A5,"London")
    - ### _Syntax_
          =COUNTIF(A2:A5,A4)

   <p align="center">
  <img src="https://github.com/Eggcelen1/G2-Midterms/assets/144224540/37f7d65d-eef8-4afb-9d92-d7388705b1e4">
</p>

  - ## AND function
    ☆ Use the **AND** function, one of the logical functions, to determine if all conditions in a test are TRUE.

    - ### _Syntax_
          =AND(A2>1,A2<100

   <p align="center">
  <img src="https://github.com/Eggcelen1/G2-Midterms/assets/144224540/ec82badc-096b-47b4-9f10-f14fc86badbb">
</p>

  - ## IF(AND) function
    ☆ Displays the value in cell A2 if it’s less than A3 AND less than 100, otherwise it displays the message "The value is out of range".
    - ### _Syntax_
          =IF(AND(A2<A3,A2<100),A2,"The value is out of range")
    ☆ Displays the value in cell A3 if it is greater than 1 AND less than 100, otherwise it displays a message. You can substitute any message of your choice.
    -  ### _Syntax_
              =IF(AND(A3>1,A3<100),A3,"The value is out of range")

   <p align="center">
  <img src="https://github.com/Eggcelen1/G2-Midterms/assets/144224540/31cd356c-ec9d-4ce4-a803-a8d14ae0e9f4">
</p>

-------------------------------------------------------------------------------------------------------------------------

   <p align="center">
  <img src="https://github.com/Eggcelen1/G2-Midterms/assets/144224540/0f3d36e9-25e5-40f8-84be-a5563b730d48">
</p>

  - ## ISEVEN function
    ☆ Returns TRUE if number is even, or FALSE if number is odd.
    
    - ### _Syntax_
          =ISEVEN(number)
   <p align="center">
  <img src="https://github.com/Eggcelen1/G2-Midterms/assets/144224540/918de40c-61bf-4fe3-92ba-18069d3cf0c7">
</p>

  - ## ISODD function
    ☆ Returns TRUE if number is odd, or FALSE if number is even.

    - ### _Syntax_
          =ISODD(number)
   <p align="center">
  <img src="https://github.com/Eggcelen1/G2-Midterms/assets/144224540/fd891876-ed05-4adb-89d4-b9f413da32ea">
</p>

  - ## ISFORMULA function
    ☆ Checks whether there is a reference to a cell that contains a formula, and returns TRUE or FALSE.
    
    - ### _Syntax_
          =ISFORMULA(reference)
   <p align="center">
  <img src="https://github.com/Eggcelen1/G2-Midterms/assets/144224540/cb2fcca0-21eb-4023-83c4-ca038ff59e12">
</p>

  - ## ISTEXT function
    ☆ Checks whether the value in cell , is having text.

    - ### _Syntax_
          =ISTEXT(value)
   <p align="center">
  <img src="https://github.com/Eggcelen1/G2-Midterms/assets/144224540/e62a63f9-0b98-4cd7-a2e4-e1eac495553c">
</p>

  - ## ISNONTEXT function
    ☆ Value refers to any item that is not text. (Note that this function returns TRUE if the value refers to a blank cell.)

    - ### _Syntax_
          =ISNONTEXT(value)
   <p align="center">
  <img src="https://github.com/Eggcelen1/G2-Midterms/assets/144224540/22acd329-41ef-4ae6-8935-a1480bc9b7b9">
</p>

-------------------------------------------------------------------------------------------------------------------------

   <p align="center">
  <img src="https://github.com/Eggcelen1/G2-Midterms/assets/144224540/c7e889eb-28a6-4f54-a294-5342144822bd">
</p>

  - ## DATE function
    ☆ The **DATE** function returns the sequential serial number that represents a particular date.

    - ### _Syntax_
          =DATE(year,month,day)
   <p align="center">
  <img src="https://github.com/Eggcelen1/G2-Midterms/assets/144224540/48a6f33d-ff17-4db9-b317-3e4a05168674">
</p>

  - ## EOMONTHfunction
    ☆ Returns the serial number for the last day of the month that is the indicated number of months before or after start_date. Use EOMONTH to calculate maturity dates or due dates that fall on the last day of the month.

    - ### _Syntax_
          =EOMONTH(start_date, months)
   <p align="center">
  <img src="https://github.com/Eggcelen1/G2-Midterms/assets/144224540/932fc5ba-6e51-4565-aba2-a57cf16446bd">
</p>

  - ## DAY(EOMONTH) function
    ☆ Calculate the Number of Days in Each Month:

    - ### _Syntax_
          =DAY(EOMONTH(DATE(YEAR, MONTH, DAY), MONTHS))

   <p align="center">
  <img src="https://github.com/Eggcelen1/G2-Midterms/assets/144224540/5a8496f7-5e68-4da3-9d98-2ba3c0282ea9">
</p>

  - ## DATE(WEEKDAY) function
    ☆ Calculate the First Weekday of Each Month

    - ### _Syntax_
          =DATE(Y, M, D) + (8 - WEEKDAY(DATE(Y, M, D)))
   <p align="center">
  <img src="https://github.com/Eggcelen1/G2-Midterms/assets/144224540/0b3ec47e-48a2-45a1-bb51-ff524edd2ac1">
</p>

  - ## TODAY()-(DATE) function
    ☆ Calculate the years elapsed from the data give to present

    - ### _Syntax_
          =(TODAY() - DATE(Y, M)/365
   <p align="center">
  <img src="https://github.com/Eggcelen1/G2-Midterms/assets/144224540/6e41f762-6b43-4f3b-bd3b-f6c1345cf12a">
</p>

-------------------------------------------------------------------------------------------------------------------------


   <p align="center">
  <img src="https://github.com/Eggcelen1/G2-Midterms/assets/144224540/76833866-0623-4de7-925b-c001ec9c9c7f">
</p>

  - ## VLOOKUP function
    ☆ Use the **VLOOKUP** function to look up a value in a table.

    - ### _Syntax_
          =VLOOKUP (lookup_value, table_array, col_index_num, [range_lookup]) 
   <p align="center">
  <img src="https://github.com/Eggcelen1/G2-Midterms/assets/144224540/06725ac0-1cee-4fd8-9959-1cf931db387e">
</p>

  - ##  XLOOKUP function
    ☆ Use the **XLOOKUP** function to find things in a table or range by row. For example, look up the price of an automotive part by the part number, or find an employee name based on their employee ID.

    - ### _Syntax_
          =XLOOKUP(lookup_value, lookup_array, return_array, [if_not_found], [match_mode], [search_mode])
   <p align="center">
  <img src="https://github.com/Eggcelen1/G2-Midterms/assets/144224540/0fbc8b74-4016-4702-a7b8-89d22a0bdfb6">
</p>  

  - ##  CHOOSE function
    ☆  Uses index_num to return a value from the list of value arguments. Use CHOOSE to select one of up to 254 values based on the index number. For example, if value1 through value7 are the days of the week, **CHOOSE** returns one of the days when a number between 1 and 7 is used as index_num.

    - ### _Syntax_
           =CHOOSE(index_num, value1, [value2], ...)
   <p align="center">
  <img src="https://github.com/Eggcelen1/G2-Midterms/assets/144224540/ade64411-a3f4-4a51-a9b3-d0b31690f335">
</p>  
   <p align="center">
  <img src="https://github.com/Eggcelen1/G2-Midterms/assets/144224540/12a43c7d-1643-429e-9094-9b260d77a7d4">
</p>  

  - ## ADDRESS function
    ☆ You can use the **ADDRESS** function to obtain the address of a cell in a worksheet, given specified row and column numbers.
    
    - ### _Syntax_
          =ADDRESS(row_num, column_num, [abs_num], [a1], [sheet_text])
         
   <p align="center">
  <img src="https://github.com/Eggcelen1/G2-Midterms/assets/144224540/3b462e46-111f-4ac5-8a40-a9ac2ff91427">
</p>


  - ## INDIRECT function
    ☆  Use INDIRECT when you want to change the reference to a cell within a formula without changing the formula itself.

    - ### _Syntax_
          =INDIRECT(ref_text, [a1]) 
   <p align="center">
  <img src="https://github.com/Eggcelen1/G2-Midterms/assets/144224540/06c3725c-ff24-4560-8dd7-87695faf0c4c">
</p>  

-------------------------------------------------------------------------------------------------------------------------

<p align="center">
  <img src="https://github.com/Eggcelen1/G2-Midterms/assets/144224540/0515cd2a-f6b4-4d2d-9346-a47e528ba197">
</p>  

   <p align="center">
  <img src="https://github.com/Eggcelen1/G2-Midterms/assets/144224540/dff26a54-0ade-406a-a1c0-3cedbce5c5c0">
</p> 

