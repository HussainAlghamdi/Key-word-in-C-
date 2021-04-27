
# <div dir = rtl > Out .</dir >

#### <div dir = rtl > تستخدم لتمرير البيانات بالعنوان  لابد أنك تضع قيمة له داخل الدالة </dir >

```csharp
int initializeInMethod; 
OutArgExample(out initializeInMethod); Console.WriteLine(initializeInMethod); // value is now 44  void OutArgExample(out int number)
 {
   number = 44;
 }
``` 

