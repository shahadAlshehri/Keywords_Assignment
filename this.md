# <div dir = rtl> this </div>
## <div dir = rtl> المفهوم: </div>
---
### <div dir = rtl> هي عباره عن كلمة محجوزة في c# وتستخدم في استخدامات رئيسية من ضمنها: </div>

 <div dir = rtl> - يمكن استخدامها للإشارة لمتغير موجود في class الحالي </div>
 <div dir = rtl> - تسخدم ايضا لمناداة method من نفس الclass</div>
 
 
 ## <div dir = rtl> مثال:</div>
---
  <div dir = rtl> في هذا المثال عرفنا متغير داخل class ثم قمنا بإسناد له قيمة من method تستقبل aragument لديه نفس اسم المتغير في هذه الحالة نستخدم كلمة this للإشارة للمتغير </div>

```
class Demo
{
//instance variable
public string Message;

public void SetMessage(string Message)
{
//"this.Message" refers to instance variable 
this.Message = Message;
}
```



