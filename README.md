# Rek-rsif-ve-Extension-Metotlar
/Rekürsif -Öz Yinelemeli
            //3*4
            int result = 1;
            for (int i = 1; i < 5; i++)
                result = result * 3;
            Console.WriteLine(result);  

        }
        public class Islemler
        {
            public int Expo(int sayi , int üs)
            {if (üs < 3)
                    return sayi;
                return Expo(sayi, üs - 1) * sayi;
