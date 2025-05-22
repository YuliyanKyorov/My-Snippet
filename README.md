# My-Snippet
Spippet for C#
1. acd - Достъп до стойност в речник
int namesAge = ages["Name"];

2. adi - Добавяне на елемент към списък
numbers.Add(0);

3. ank - Добавяне на нова двойка ключ-стойност в речник
ages.Add("Name", 01);

4. anm - Използване на анонимни методи
Action<string> printString = delegate (string s) { Console.WriteLine(s); };
printString("Hello, world!");

5. bc - Проверка дали списък съдържа определен елемент
bool containsNumber = numbers.Contains(4);

6. ca -  List/Stack/Queue<Т> name = new List/Stack/Queue<Т>{ }    // създава нов празен масив

7. cl  - List/Stack/Queue<T> name = new List/Stack/Queue<T>(); //  създава нов лист стек и опашка от  вид променлива

8. cnk - Проверка дали речник съдържа определен ключ
bool hasKey = ages.ContainsKey("Bob");

9. cr - Console.ReadLine();// четене на вход от конзолата като низ (string).

10. crs - string[] name = Console.ReadLine() .Split(", "); Console.ReadLine() // Чете вход от конзолата като низ (string).
.Split(", ") – Разделя прочетения низ на поднизове, използвайки ", " (запетая и интервал) като разделител.
string[] name – Декларира масив от низове (string[]), който ще съдържа резултатите от разделянето.

11. dc - Речник Dictionary
Dictionary<object, object>

12. dic - Работа с речници (Dictionary)
Dictionary<string, int> ages = new Dictionary<string, int>()
{
    {"Name1", 01},
    {"Name2", 02}
};

13. dn - Декларация и инициализация на речник
var dic = new Dictionary<object, object>();

14.dnx - Създава нов речник 
var dic = new Dictionary<object, object>() { [0] = null };

15. fcw - Преминаване през списък с foreach цикъл
foreach (int number in numbers)
{
    Console.WriteLine(number);
}

16. fl - Филтриране на списък с LINQ
var evenNumbers = numbers.Where(n => n % 2 == 0).ToList();

17. forcw - For цикъл за обхождане и отпечатване на двумерен масив
for (int row = 0; row < numbers.GetLength(0); row++)        // редове
{
    for (int col = 0; col < numbers.GetLength(1); col++)    // колони
    {
        Console.Write(numbers[row, col] + " ");
    }
    Console.WriteLine(); // нов ред след всяка редица   
}

18. ig - Групиране на елементи по критерий
var groupedByRemainder = numbers.GroupBy(n => n % 3);

19. ipr - int name = int.Parse(Console.ReadLine());  // нов int чакащ вход от потребителя

20. lax - Използване на ламбда изрази
Func<int, int> square = x => x * x;
int result = square(5)

21. ll - Обединяване на два списъка
List<int> moreNumbers = new List<int>() { 7, 8, 9 };
var combinedList = numbers.Concat(moreNumbers).ToList();

22. lx - Празна списък от тип T променлива
List<T>

23. nc - Нов празен клас
class ClassName
{

}

24. nl - Инициализация на списък
List<int> numbers = new List<int>() { 1, 2, 3, 4, 5 };

25. no - Създаване на нов обект
MyClass myObject = new MyClass();

26. rl - Обръщане на реда на елементите в списък
numbers.Reverse();

27. rmi - Премахване на елемент от списък
numbers.Remove(0);

28. sl - Сортиране на списък
numbers.Sort();

29. ssa - int[] numbers = Console.ReadLine().Split(", ").Select(int.Parse).ToArray();//Чете входа като низ (string).
.Split(", ") – Разделя низа на части, използвайки ", " (запетая и интервал) като разделител.
.Select(int.Parse) – Преобразува всеки елемент от масива (който е string) в цяло число (int).
.ToArray() – Преобразува резултата обратно в масив от цели числа (int[]).

30. ssl - List<int> numbers = Console.ReadLine() .Split(", ") .Select(int.Parse) .ToList();//Чете входа като низ (string).
.Split(", ") – Разделя прочетения низ на поднизове, използвайки ", " (запетая и интервал) като разделител.
.Select(int.Parse) – Преобразува всеки подниз в цяло число (int).
.ToList() – Преобразува резултата в списък от цели числа (List<int>)

31. str - string name = Console.ReadLine();  //  нов стринг чакащ вход от usera

32. sysyp - namespace ConsoleApp1 {internal class Program {}} Program класът е празен и няма Main мето.

33. sysypm - namespace ConsoleApp1 { internal class Program { static void Main(string[] args) { }}//namespace ConsoleApp1
Дефинира пространство от имена (namespace), което групира класове и други типове. ConsoleApp1 е името на пространството, което обикновено съвпада с името на проекта.internal class Program Дефинира клас с име Program.Модификаторът internal означава, че този клас е достъпен само в рамките на същия проект. static void Main(string[] args) Това е главният метод (Main), който се изпълнява първи при стартиране на програмата.
string[] args – Това е масив от аргументи, които могат да се подават от командния ред.void – Методът няма връщана стойност. Тяло на метода { }

34. ua - Използване на using за автоматично освобождаване на ресурси
using (StreamWriter writer = new StreamWriter("example.txt"))
{
    writer.WriteLine("This is an example.");
}

35. uty - Използване на try-catch блокове за обработка на изключения
try
{
    // Код, който може да хвърли изключение
}
catch (Exception ex)
{
    Console.WriteLine($"Възникна грешка: {ex.Message}");
}
finally
{
    // Код, който винаги се изпълнява независимо от изключението
}

36. va - Празен масив от var променлива 
var items = new T [0];

37. vax - Декларация и инициализация на масив с T променлива 
var items = new T [] { null };


38. vn - Празен на списък стек или опашка с var променлива
var items = new List/Stack/Queue<T>( );

39. vnx - Декларация и инициализация на списък стек или опашка с var променлива
var items = new List/Stack/Queue<T>() { null };
