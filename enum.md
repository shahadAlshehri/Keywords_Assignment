# <div dir = rtl> enum </div>
## <div dir = rtl> المفهوم: </div>
---
### <div dir = rtl> هي عباره عن كلمة محجوزة في c#  تستخدم لتعريف مجموعة من القيم الثابتة وهي مفيدة في حال الرغبة في التعامل مع نوع محدد من القيم </div>

 
 ## <div dir = rtl> مثال:</div>
 ---
  ### <div dir = rtl> يوضح المثال التالي كيفية استخدام كلمة `enum` :
</div>

``` 
enum Days  { sun,mun,tue,wed,thu,fri,sat};
static void Main(string[] args)
            {
              Days a = (Days)5;
              Console.WriteLine(a);
            }
```