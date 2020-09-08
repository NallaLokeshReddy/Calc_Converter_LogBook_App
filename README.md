# Calc_Converter_LogBook_App
Android app: Calculator with Unit Converter and Log Book for Dairy farmers

Most of my villager's source of income is mainly from dairy farming. This app is developed for our rural people whose daily routine involves
purchases at general stores and/or fertilizer suppliers : requires basic arithmetic calculations
land measurements: requires conversion of various units of length and area and pouring milk to the nearby dairy centers: requires a logbook to enter the milk supplied on a session (morning or evening) basis and calculation of average rate per litre.

App has four screens and key features of each screen are as follows.

Calculator:
The calculator is built such that arithmetic operations are solved based on BODMAS rule.
All the arithmatic operations (a click on 'equal to' symbol is considered as one operation) performed are stored in text (.txt) format, which helps to calculate GRAND TOTAL (GT: is the sum of answers of each operation).

Calc History:
The stored operations on calculator are displayed on Calc History screen when it is called.

Unit Converter:
User is allowed to pick a parameter (Area, Length). Based on chosen parameter, the respective units are visible on both unit selectors.
The available units for Area parameter are Acre, Ankanam in Nellore, Ankanam in Tirupati, Cent, Chadaram, Gajam/Sq. Yard, Gunta in Chittoor, Gunta in other places, Hectare, Square Foot.
The available units for Length parameter are Chain, Foot, Inch, Link, Yard.

Log Book:
First Bill cycle is from date 1 to 15 of a month. Second Bill Cycle is from date 16 to the end of a month.

The data can be entered for first bill cycle from 1st to 20th of a current month and for second bill cycle from 16th of a current month to 5th of a next month.                                                                                                                                                                                                                                             If you try to Choose Date out of this range, you will be thrown an error message.  
Note: The reference for all the chosen date is phone's clock.

For each session, input the data for Total litres poured and Total amount priced. App displays you average rate per litre when 'view' button is clicked. Use 'save' button to store the data. 

User must input data for both sessions when one of them is already entered. No worry, it will alert user whenever he/she tries to miss out a session.

App also alerts user, when user try to enter data for 

The days he/she already provided.
 Future days
15th of first bill cycle during 15th to 20th of a month and for date beyond 28th of a second bill cycle during 28th of current month to 5th of a next month. The alert message seeks for the confirmation of last entry from the user.

Based on phone's date, list of months and billing cycles are available in the month and bill cycle pickers.                                        

'View' button helps to display  the consolidated statement, consists of total litres poured, total amount priced and average rate per litre, of the chosen month and cycle. 

'Generate PDF' button helps to generate a pdf file of a billing statement, in a tabular form, for a chosen bill cycle. The last row of a table provides the net sum of litres poured, priced and average rate per litre for each session.

The billing details are sorted out based on date in an ascending order. So users can input the data for any day in any order i.e., entry days need not to be consecutive.

'Clear Data' button pops up with an alert message window seeking for removal of current billing cycle entries.
