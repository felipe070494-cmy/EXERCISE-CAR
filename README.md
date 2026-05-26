# EXERCISE-CAR
using System;

class Car
{
    string color; //campo en blanco
    int maxSpeed; // campo en blanco

static void Main(string[] args)
{
// dentro del Main();
Car myObj = new Car();
myObj.color = "red";
myObj.maxSpeed = 200; 

Console.WriteLine (myObj.color);
Console.WriteLine (myObj.maxSpeed);

}
}



using System;

class Car 
{
    public string model;
    public string color;
    public int year;
}

class Program
{
    
    static void Main(string[] args) 
    {
       
        Car ford = new Car(); 
        ford.model = "Mustang";
        ford.color = "red";
        ford.year = 1969;

        
        Car opel = new Car();
        opel.model = "Astra";
        opel.color = "White"; 
        opel.year = 2005;
        
      
        Console.WriteLine(opel.model);
        Console.WriteLine(opel.color);
        Console.WriteLine(opel.year);
    }
}


using System;

class MyClass
{
    string color = "red";
    int maxSpeed = 200;

    public void FullThrottle()
    {
        Console.WriteLine("The car is going as fast as it can!");
    }

    static void Main(string[] args)
    {
        MyClass myObj = new MyClass();

        Console.WriteLine(myObj.color);
        Console.WriteLine(myObj.maxSpeed);

        myObj.FullThrottle();
    }
}
