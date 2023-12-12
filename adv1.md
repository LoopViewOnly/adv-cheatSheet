<img src="https://res.cloudinary.com/monday-platform/image/upload/v1687508245/board_views_images/logos/1687508245192_546ddd78-f911-1be8-ace5-26033aa68ede.png" width="100">

# Loop C#

###  Data types - انواع متغيرات
- int - عدد صحيح &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; int age=10; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(1 , 94 , -18 , 0 , 34874)

- double - عدد كسري &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;double x=45.6;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;(20.6 , 97.5 , -48.333)

- string - نص &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;string name = "Looper";&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;("Husam" , "Hello" , "Rex")

---

###  Define Variables - تعريف متغيرات
```cs
- int age = 10;
- double height = 1.74;
- string name = "Elon";
```

---
### Output - مخرجات
```cs
Console.Write();        //--> print only
Console.WriteLine();    //--> print + make new line
//Examples امثلة 
Console.WriteLine("Hello Loopers"); // --> Hello Loopers
Console.WriteLine("age");           // --> age

Console.WriteLine(age);       // --> 10
Console.WriteLine(age + 5);   // --> 15

Console.WriteLine("My age is "+age);   // --> My age is 10
```

---
### Math operations - عمليات حسابية
```cs
Console.WriteLine(x+y);   // --> جمع
Console.WriteLine(x-y);   // --> طرح
Console.WriteLine(x*y);   // --> ضرب
Console.WriteLine(x/y);   // --> قسمة
```


---
### Input - المدخلات
```cs
string name = Console.ReadLine();               // استقبال متغير من نوع نص
int age = int.Parse(Console.ReadLine());        // استقبال متغير من نوع عدد صحيح
int average = double.Parse(Console.ReadLine()); // استقبال متغير من نوع عدد كسري
```
---
### if
###### (< , > , <= , >= , == , !=)
```cs
if(marks == 100) {Console.Write("Excellent");}
if(age >= 80) {Console.Write("Good");}
if(age < 80) {Console.Write("Not Good");}
```

### if else ( &&-and , ||-or )
```cs
if( age >= 10 && age <=18 ) 
{
    Console.Write("Teenager");
}
else
{
    Console.Write("Not A Teenager");
}
```

### Modulo % (باقي القسمة)
###### x%y =  y على x كم يتبقى من عملية قسمة 
```cs
Console.Write(5%2); // 1 
Console.Write(9%5); // 4
```

### for
###### for ( التغير ; الشرط ; البداية )
```cs
for(int i=0 ; i<10 ; i++) //برنامج يطبع الاعداد من 0-9 
{
    Console.WriteLine(i);
}
```

### while
###### while (الشرط) يجب ان يتحقق الشرط من اجل تنفيذ المطلوب
```cs
int n=0;
while(n<=10) // برنامج يطبع الاعداد من 0-10 
{
    Console.Write(n+",");
    n++;
}
```
