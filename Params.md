# <div dir = rtl> params </div>
## <div dir = rtl> المفهوم: </div>
---
### <div dir = rtl> تستخدم كلمة  `params` لتحديد دالة تأخذ عدد متغير من arguments وهي مفيده في حالة عدم التأكد من عدد arguments التي يجب ارسالها ك parameter لدالة</div>

 
 
 ## <div dir = rtl> مثال:</div>

---
### <div dir = rtl> يوضح المثال التالي كيفية استخدام كلمة `params` :
</div>

```

        public static void UseParams(params int[] list)
    {
      for (int i = 0; i < list.Length; i++)
        {
        Console.WriteLine(list[i] + " ");
        }
        
    }   
      UseParams(7, 9, 10);

```