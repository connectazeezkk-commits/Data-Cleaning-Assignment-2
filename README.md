Missing Value Count;-           =CountBlank(Select, Price Column Full).
Missing Value ;-                =IF(Isblank(Select, Price Row),Average(Select, Price Column Full),Select, Price Row again).
Inconsistent Text ;-            =Proper(What mentioned Row) E.g.; Product Name Full Column.
Missing Category ;-             =IF(Isblank(Select, Mentioned Row),"Unknown", Again select Mentioned Row) E.g.;-Select Category Raw.
Find & Replace, Misspelling ;-   Cntrl+F, then select Replace Option, Then type what we need to change from Category Column and Fill right words the select Replace all.
Removing Duplicates ;-           Select all column, then go to Data bar, then select Remove Duplicates Option, after that we can select, what we need column or all column, then press OK button.
Split Column ;-                  Create new separate columns then use Left and Right Function, E.g., =Left or Right(select product Id row, type How many letters are needed).
Merge Date ;-                   =Select, Which column first we need&"space"&Select, which column second we need. E.g.;- =Product name row & " "& Brand name row. (=B2&" "&D2)


