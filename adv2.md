<img src="https://res.cloudinary.com/monday-platform/image/upload/v1687508245/board_views_images/logos/1687508245192_546ddd78-f911-1be8-ace5-26033aa68ede.png" width="100">

# Loop C#

### Arrays - مصفوفة
###### the following code shows 2 different ways to define the same array
###### البرنامج التالي يعرض طريقتين مختلفتين لتعريف ذات المصفوفة
```cs
int[] arr1 = {80,96,100,55,76};

int[] arr2 = new int[5];
arr[0] = 80;
arr[1] = 96;
arr[2] = 100;
arr[3] = 55;
arr[4] = 76;
```
###### arr.Length = عملية ترجع حجم المصفوفة
```cs
 for(int i=0 ; i<arr1.Length ; i++) //print all array values on seperate lines
  {
      Console.WriteLine(arr1[i]);
  } 
```

### functions - عمليات
```cs
static void sayHi(string name) //void(فراغ) من نوع sayHi عملية باسم 
{
  Console.Write("Welcome "+name);
}
```

```cs
static int sum(int g1 , int g2)//int من نوع sum عملية باسم 
{
  return g1+g2;
}
```

```cs
static double avg(int g1 , int g2 , int g3)//double من نوع avg عملية باسم 
{
  return (g1+g2+g3)/3;
}
```