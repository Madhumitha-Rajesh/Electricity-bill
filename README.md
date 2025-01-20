# Electricity-bill


public class ElectricBill
 {
 public static void main(String args[])
 {
 int units = 123;
 int bill = 0;
 
 if (units > 100)
 {
 if (units >= 200)
 {
 if (units > 300)
 {
 bill = units * 8;
 }
 elsebill = units * 6;
 }
 else
 bill = units * 5;
 }
 System.out.println("CHENNAI ELECTRICITY LTD, CHENNAI");
System.out.println("Units Consumed : " + units);
System.out.println("Total Bill : " + bill);
 }
 }

 output- 

 -- Electricity Bill Calculation --
Enter the number of units consumed: 300

Units Consumed: 300
Bill Amount (before surcharge): 805.00
Surcharge (20%): 161.00
Total Bill Amount: 966.00
