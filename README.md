- š Hi, Iām @tmhwong
- š Iām interested in ... game development
- š± Iām currently learning ... c#
- šļø Iām looking to collaborate on ... creativeness
- š« How to reach me ... tmhwong88@gmail.com

<!---
tmhwong/tmhwong is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

using System;
namespace primeNumbers
{
    class MyApplication
    {
        public static void Main()
        {
            int n = 15, a = 0;
            for (int i = 1; i <= n; i++)
            {
                if (n % i == 0)
                {
                    a++;
                }
            }
            if (a == 2)
            {
                Console.WriteLine("{0} is a Prime Number", n);
            }
            else
            {
                Console.WriteLine("The number is not a Prime Number");
            }
            Console.ReadLine();
        }
    }
}
