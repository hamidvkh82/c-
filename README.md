# c#


namespace BasicCSharpTutorial
{
    class Program




















        // تابع اصلی برنام

        static void Main(string[] args)
        {
            // چاپ متن در خروجی
            Console.WriteLine("سلام به دنیای سی شارپ!");

            // تعریف متغیرها
            int age = 22;
            string name = "علی";


            

            // نمایش اطلاعات کاربر
            Console.WriteLine($"نام من {name} است و {age} سال دارم.");

            // شرط ساده
            if (age >= 18)
            {
                Console.WriteLine("شما بزرگسال هستید.");
            }
            else
            {
                Console.WriteLine("شما هنوز کودک هستید.");
            }

            
            Console.WriteLine("شمارش از 1 تا 5:");
            for (int i = 1; i <= 5; i++)
            {
                Console.WriteLine(i);
            }

            // استفاده از تابع ساده
            int result = AddNumbers(3, 5);
            Console.WriteLine($"جمع 3 و 5 برابر است با {result}");
        }

        // تعریف تابع
        static int AddNumbers(int a, int b)
        {
            return a + b;
        }
    }
}

            // حلقه For برای شمارش
Comprehensive C# code snippet
