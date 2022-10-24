//Zad1
/*
Console.WriteLine("Podaj liczbe: ");
int n= int.Parse(Console.ReadLine());
for (int i = 0; i < n; i++)
{
    Console.Write("*-|");
}
*/
//Zad2
/*
Console.WriteLine("Podaj liczbe: ");
int n = int.Parse(Console.ReadLine());
for (int i = 0; i < n; i++)
{
    Console.Write("∗|| ∗ ∗ − − ∗ ∗ ");
}
*/
//Zad3
/*
Console.WriteLine("Podaj liczbe: ");
int n = int.Parse(Console.ReadLine());
for (int i = 0; i < n; i++)
{
    Console.Write("∗| ∗ − − ∗||| ∗ − − − − ");
}
*/
//ZadA - Tabliczka Mnożenia
/*
for(int i = 1; i < 11; i++)
{
    for (int j = 1; j < 11; j++)
    {
        Console.Write(i * j + "\t");
    }
    Console.WriteLine();
}
*/
//ZadB - PRE - Narysuj Poniższe kształty
/*
1.
*
**
***
**** 
2.
****
***
**
*
3.
   *
  **
 ***
****
*/
//1.
/*
int n = int.Parse(Console.ReadLine());
for (int i = 0; i < n; i++)
{
    for (int j = 0; j < i + 1; j++)
    {
        Console.Write("*");
    }
    Console.WriteLine();
}

Console.WriteLine();
Console.WriteLine();
*/
//2.
/*
int n = int.Parse(Console.ReadLine());
for (int i = 0; i < n; i++)
{
    for (int j = 0; j <n-i; j++)
    {
        Console.Write("*");
    }
    Console.WriteLine();
}

Console.WriteLine();
Console.WriteLine();
*/
