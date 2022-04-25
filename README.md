# single-inheritance


 { class a
        {
            public void basemethod()
           
            
            {
                Console.WriteLine("this is base class:");

            }
            
        }
        class b:a
        {
            public void drivedmethod()
            {
                Console.WriteLine("this is drived class:");
            }

        }

        static void Main(string[] args)
        {
            b obj = new b();
            Console.WriteLine("this is all class:");
            Console.ReadLine();
            
        }
    }
