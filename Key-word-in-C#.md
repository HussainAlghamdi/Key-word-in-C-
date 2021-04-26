# Abstract

#### Abstract classes are classes that are used to inherit fields and functions from, but it can not be instantiated to an object.

```csharp
public abstract class shape
    {

        public abstract void draw();


    }

    public class square : shape
    {

        public override void draw()
        {
            Console.WriteLine("square..");
        }
    }
    public class Rectangel : shape
    {

        public override void draw()
        {
            Console.WriteLine("Rectangel..");
        }
    }
```
# 
# Class
#### a class contains similar features and methods to an object, it also can group any objects sharing similarities in a so called oop pillar called polymorphism.

```csharp
class Car 
{
  string color = "red";

  static void Main(string[] args)
  {
    Car myObj = new Car();
    Console.WriteLine(myObj.color);
  }
}
``` 
# 
# As 
#### As is mainly used for type casting between objects.
```csharp
abstract class Shape  
{ } 
class Rec : Shape  
{ } 
class f  
{  
void ff()  
{  
Shape rec = new Rec(); 
Rec rec1 = (rec as Rec);  
}  
}
``` 


# Goto 
#### Goto is used to jump between labels to ease the change in labels. 
```csharp
static void Main(string[] args)
        {
        print:
            Console.WriteLine("write a string that contains 7");
            string s = Console.ReadLine();
            *//*if (s.Contains("7"))
            {
                Console.WriteLine("Nice");
            }
            else
            {
                goto print;
            }*//*

            if (!s.Contains("7"))
                goto print;
        }
``` 



# Base
#### Base means the direct ancestor of a derived class in inheritance.

```csharp
 public MessegDecorator(string messeg)
        {
            this.messeg = messeg;
            Console.WriteLine("bacs has in");
        }
        public virtual string decoretor()
        {
            return "[:" + this.messeg + ":]";
        }

        public class EasyMessegDecorator : MessegDecorator
        {
            public EasyMessegDecorator(string messeg) : base(messeg)
            {
                Console.WriteLine("subclasss has in");

                //this.messeg = messeg;

            }
            public override string decoretor()
            {
                return "***" + this.messeg + "***";
            }

        }
``` 

# delegate
#### delegate is a method pointer that save the references of the methods assigned to it. 

```csharp
public delegate int del(int a, int b);
        static void Main(string[] args)
        {
            del del = sum;
            Console.WriteLine(del(1, 2));
            
        }
        static int sum(int a, int b)
        {
            return a + b;
        }
``` 
