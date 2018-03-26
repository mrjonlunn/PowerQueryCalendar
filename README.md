# PowerQueryCalendar
M language/Power Query Calendar

Basic calendar for Power BI, using the Power Query Langauge M

Columns are (with some examples)
Calendar Key

Date - dd/mm/yyyy

Day Short Name - Mon, Tue etc

Day Long Name - Monday, Tuesday

Day of Week - 0-6 starting at Monday

Is Week Day - 1 or 0

Month Key - 1 to 12

Month Short Name - Jan, Feb

Month Long Name - January

Month Year Name - Jan-18

Month Year Key - 201801

Quarter Of Year - 1 to 4

Quarter Name - Q01 to Q04

Quarter Year Name - Q01-18

Quarter Year Key 201801

Year - 2018


All columns after date are calulated on the Date column, so can be removed if not needed as there are no inter-dependances
Key columns are used in Power BI to in the 'Sort By Another Coumn' function so that Months, etc are not sorted alphabetically.

