# fibonaccidiziortalamahesaplamas-
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 Console.Write("Sayı: ");
            double length = Convert.ToInt32(Console.ReadLine());
            int a = 0;
            int b = 1;
            int toplam = 1;
            for (int i = 3; i <= length; i++)
            {
                int c = a + b;
                toplam += a + b;
                a = b;
                b = c;

            }
            double ortalama = toplam / length;
            Console.WriteLine($"Ortalama = {ortalama}");

            Console.ReadLine();
        }
