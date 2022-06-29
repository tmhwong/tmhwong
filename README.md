- 👋 Hi, I’m @tmhwong
- 👀 I’m interested in ... game development
- 🌱 I’m currently learning ... c#
- 💞️ I’m looking to collaborate on ... creativeness
- 📫 How to reach me ... tmhwong88@gmail.com

<!---
tmhwong/tmhwong is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
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
