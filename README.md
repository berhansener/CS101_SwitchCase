# CS101_SwitchCase

```cs
using System;

    namespace swithCase
    {
        class Program

        {
            static void Main(string[] args)

            {
                int month= DateTime.Now.Month;

                //Expression
                switch (month)
                {
                    case 1:
                        Console.WriteLine("ocak ayındasınız");
                        break;
                    case 2: 
                        Console.WriteLine("şubat ayındasın");
                        break;
                    case 3:
                        Console.WriteLine("mart ayındasın");
                        break;                       

                    case 4:
                        Console.WriteLine("nisan ayındasın");
                        break;


                    default:
                        Console.WriteLine("aralık ayındasın");
                    break;


                
                }
                switch (month)

                {

                    case 12:
                    case 1:
                    case 2:
                        Console.WriteLine("kış mevsimi");
                        break;
                    case 3:
                    case 4:
                    case 5:
                        Console.WriteLine("bahar mevsimi");
                        break;
                    case 6:
                    case 7:
                    case 8:                    
                        Console.WriteLine("yaz mevsimi");
                        break;
                    case 9:
                    case 10:
                    case 11:
                        Console.WriteLine("soonbahar mevsimi");
                        break;
                    default:
                    break;

                }
            }
        }


    }

```
