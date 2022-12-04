Console.WriteLine("Введите а="); int a = Convert.ToInt32(Console.ReadLine()); 
Console.WriteLine("Введите в="); int b = Convert.ToInt32(Console.ReadLine());
Console.WriteLine("Введите c="); int c = Convert.ToInt32(Console.ReadLine());

int max = a;

if ( b > max ) max = b;
if ( c > max ) max = c;

    Console.WriteLine("max="); Console.WriteLine(max);