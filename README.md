**VariableAlgo_Csharp

https://docs.google.com/document/d/1QE5ehwrZMl3L1bQZZSTEPnnpQ6x16m1GRjPFAKHzAN0/edit

## Variables class
https://docs.google.com/document/d/1dzUA39n5rpA58U-fVgl7sXR9rz0-BTdJoVd__MU6QdU/edit
            // Variables Algorith practice



        **declared and initialized a variable
            // camelCase with the variable name
            //explicit typing
            string dogName = "Rolf";
            int dogAge = 10;
            char nickName = 'R';
            bool lovesHiking = true;
            double tennisBalls = 32;
            decimal weight = 70.2m;

            **Concatenate these variables in a Console.Writeline();

            Console.WriteLine($"My dog's name is {dogName}, He is {dogAge} years old");
            Console.WriteLine("-------------------------------------");


           ** String interpolation with  $ and the {} around the variables

            Console.WriteLine($"My dog's name is {dogName},\n He is {dogAge} years old and has {tennisBalls} tennisballs \n and it is {lovesHiking} that he loves to hike");

            Console.WriteLine("-------------------------------- \n");
             **Boolean condition
            if (lovesHiking == true)
            {
                Console.WriteLine($"{dogName} loves to hike !");
            }
            else
            {
                Console.WriteLine($"{dogName} hates to hike !");
            }