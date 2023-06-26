Code for an activity proposed by the C# course on the udemy.com website.

A Brazilian car rental company charges an hourly rate for rentals of up to 12 hours. However, if the duration of the rental exceeds 12 hours, the rental will be charged on a daily basis. In addition to the lease amount, it is added to the price the value of the tax according to the rules of the country which, in the case of Brazil, is 20% for amounts up to 100.00, or 15% for amounts above 100.00. Make one program that reads location data (car model, initial and final time of lease), as well as the hourly rate and daily lease rate. The program must then generate the payment note (containing the lease amount, the tax and total payment amount) and inform the data on the screen. See the examples.  

Example 1:  

Enter rental data  
Car model: **Civic**  
Pickup (dd/MM/yyyy hh:mm): **25/06/2018 10:30**  
Return (dd/MM/yyyy hh:mm): **25/06/2018 14:40**  
Enter price per hour: **10.00**  
Enter price per day: **130.00**  
INVOICE:  
Basic payment: 50.00  
Tax: 10.00  
Total payment: 60.00  

*Calculations:*  
*Duration = (25/06/2018 14:40) - (25/06/2018 10:30) = 4:10 = 5 hours*  
*Basic payment = 5 * 10 = 50*  
*Tax = 50 * 20% = 50 * 0.2 = 10*  

----------------------------------------------  
Example 2:  

Enter rental data  
Car model: **Civic**  
Pickup (dd/MM/yyyy hh:mm): **25/06/2018 10:30**  
Return (dd/MM/yyyy hh:mm): **27/06/2018 11:40**  
Enter price per hour: **10.00**  
Enter price per day: **130.00**  
INVOICE:  
Basic payment: 390.00  
Tax: 58.50  
Total payment: 448.50  

*Calculations:*  
*Duration = (27/06/2018 11:40) - (25/06/2018 10:30) = 2 days + 1:10 = 3 days*  
*Basic payment = 3 * 130 = 390*  
*Tax = 390 * 15% = 390 * 0.15 = 58.50*  
