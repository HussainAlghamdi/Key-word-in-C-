# <div dir = rtl > Ref .</dir >

#### <div dir = rtl >  تستخدم لتمرير البيانات بالعنوان بقيمة مسبقة </dir >

```csharp
void Method(ref int refArgument)
{ 
  refArgument = refArgument + 44; 
} 
int number = 1;
Method(ref number); 
Console.WriteLine(number); 
// Output: 45
```

