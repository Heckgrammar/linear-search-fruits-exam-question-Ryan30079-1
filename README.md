namespace LinearSearchFruitsTask
{
    internal class Program
    {
        static void Main(string[] args)
        {
            string[] fruits = { "banana", "apple", "orange", "pear", "grape", "pineapple" };
            Console.WriteLine("What word would you like to find?");
            string word = Console.ReadLine();
            if (fruits.Contains(word.ToLower()))
            {
                Console.WriteLine("true");
            }
            else
            {
                Console.WriteLine("false");
            }

            string[] cars = { "honda", "bmw", "mercedes", "volvo", "jaguar", "tesla" };
            Console.WriteLine("What car are you looking to buying?");
            string choice = Console.ReadLine();
            if (cars.Contains(choice.ToLower()))
            {
                Console.WriteLine("Okay");
            }
            else
            {
                Console.WriteLine("Sorry, we don't have that car.");
            }
        }
    }
}
