Missing Value Count;-           =CountBlank(Select, Price Column Full).
Missing Value ;-                =IF(Isblank(Select, Price Row),Average(Select, Price Column Full),Select, Price Row again).
Inconsistent Text ;-            =Proper(What mentioned Row) E.g.; Product Name Full Column.
Missing Category ;-             =IF(Isblank(Select, Mentioned Row),"Unknown", Again select Mentioned Row) E.g.;-Select Category Raw.
Find & Replace, Misspelling ;-   Cntrl+F, then select Replace Option, Then type what we need to change from Category Column and Fill right words the select Replace all.
Removing Duplicates ;-           Select all column, then go to Data bar, then select Remove Duplicates Option, after that we can select, what we need column or all column, then press OK button.
Split Column ;-                  Create new separate columns then use Left and Right Function, E.g., =Left or Right(select product Id row, type How many letters are needed).
Merge Date ;-                   =Select, Which column first we need&"space"&Select, which column second we need. E.g.;- =Product name row & " "& Brand name row. (=B2&" "&D2)
Currency Format;-                Create new column, then copy 'Price' Column and paste to new column, after that go to 'General' option then change Currency format.
Date Format;-                    Go to 'Formulas Bar' then select Date&Time, then select Date, after that fill Year & Month then select arrow button in the Day column, then select Which column we need(Mfg;Date row,(J2), then OK. E.g. =Date(2026-01-J2).
Conditional Format;-             Select 'Price' column, go to Home bar, then select Conditional Formatting and select which option we need.
Category Highlights;-            Go to Conditional formatting, select Highlight cells rules, then select, 'Text that contains' select which cells we need and select, 'with' option and select which option we need. 
