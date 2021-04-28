# <div dir = rtl > Params.</dir >

#### <div dir = rtl > طريقة تستخدم لاستقبال مجموعه من المدخلات في لسته واحده . </dir >

```csharp
 static void Main(string[] args)
        {
        UsePrams(1, 'a', "hi");
        }
public static void UsePrams(params object[] List)
        {
            for (int i = 0; i < List.Length; i++)
            {
                Console.WriteLine(List[i]+" ");
            }
            Console.WriteLine();
        }
        
```

