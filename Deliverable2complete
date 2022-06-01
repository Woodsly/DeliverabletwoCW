using System;

namespace Deliverable2
{
    internal class Program
    {
        static void Main(string[] args)
        {
   
            decimal total;
            decimal eatprice = 9.99M;
            decimal water = 0.00M;
            int watercount = 0;
            decimal DrPep = 2.50M;
            int DrPepcount = 0;
            int party;
            int partycount = 1;
            string customerchoice;

            Console.WriteLine("Hello!  Welcome to our Buffet.  All you can eat for only $9.99!  We charge extra for Dr Pepper.  How many peopple are in your group?  Please, parties of 6 or lower.");
            party = int.Parse(Console.ReadLine());
            if (party <= 6)
                {
                Console.WriteLine("A table for " + party + "! Please follow me and take a seat.");
                } else
                {
                Environment.Exit(0);
                }
            while (partycount <= party)
                    {
                    Console.WriteLine("Alright, person number " + partycount + ", water or Dr Pepper?");
                    customerchoice = Console.ReadLine().ToLower();
                if (customerchoice == "dr pepper")
                {
                    Console.WriteLine("Dr Pepper, great choice!");
                    DrPepcount++;
                }
                else if (customerchoice == "water")
                {
                    Console.WriteLine("Water, sounds good!");
                    watercount++;
                }
                else
                {
                    Console.WriteLine("We don't have that.  No drink for you!");
                }

                partycount++;
                    }
            Console.WriteLine("OK, so that's " + watercount + " waters, and " + DrPepcount + " Dr Peppers.  I'll be right back. Feel free to grab your food!");
            decimal dpprice = (Decimal)DrPepcount * DrPep;
            total = (Decimal)party * (Decimal)eatprice + dpprice;
            Console.WriteLine(total + " is your total.  Feel free to pay whenever no rush.");
        }
    }
}
