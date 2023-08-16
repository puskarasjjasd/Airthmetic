//# Airthmetic
//Airthmetic .net core
{

    Console.WriteLine("Hello,would you like to use calculater! (Yes/NO)");

    String ?isUserInput = Console.ReadLine();


    if (isUserInput == "Yes")

    {
        int Result;
        //int x = 10, y = 5;
        Console.Write("Please Enter First Digit: ");
        int x = Convert.ToInt32(Console.ReadLine());
        Console.Write("Please enter Second Digit: ");
        int y = Convert.ToInt32(Console.ReadLine());


        //Addition

        Result = (x + y);
        Console.WriteLine("Addition Operator: " + Result);

        //Subtraction

        Result = (x - y);
        Console.WriteLine("Subtraction Operator: " + Result);

        //Multiplication

        Result = (x * y);
        Console.WriteLine("Multiplication Operator: " + Result);

        //Division

        Result = (x / y);
        Console.WriteLine("Division Operator: " + Result);
        Console.ReadLine();

    }
    else
    {
        Console.WriteLine("Thank you !!");
        Console.ReadLine();
    }

}
