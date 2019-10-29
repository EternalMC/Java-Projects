
Conversion Character	Description	Example	Results
s	Displays a simple string	String.format( "%s", "hello");	"hello"
S	Converts string to upper case	String.format( "%S", "hello");	"HELLO"
d	Displays value as base-10 integer	String.format( "%d", 12);	"12"
E or e	Formats the number in scientific (exponential) notation.	String.format( "%E", 12.4);
String.format( "%e", 12.4);	"1.240000E+001"
"1.240000e+001"
f	Formats the number as a decimal	String.format( "%f", 12.4);	"12.400000"
tD	Displays the date in month/day /year or other local format.	String.format( "%tD",  
Calendar.getInstance( ));	"11/31/2011"
tF	Displays the date in year-month-day format.	String.format( "%tF",
Calendar.getInstance( ));	"2011-11-31"
tT	Displays the 24-hour time from the input Calendar.	String.format( "%tT", Calendar.getInstance( ));	"13:34:18"
tr	Displays the 12-hour time with AM/PM.	String.format( "%tr",
Calendar.getInstance( ));	"1:34:18 PM"
%	Displays a percent character	String.format( "%%" );	"%"
n	Adds a newline character to the string	String.format( "hop%nscotch" );	"hop
scotch"
