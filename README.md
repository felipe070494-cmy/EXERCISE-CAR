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
