# Switch-Statements

Switch statements are unique because they act similar to an if-else statement code. It is a more elegant way to test a variable for equality against a list of values. A variable is put into a switch statement and goes through "cases" which is a value that is being checked for equality with the variable. If the case matches, then the case is executed and all following cases are voided due to the break statement in the case. 
For example,
int num = 2;
switch(num)
{
case 1:
Console.WriteLine("One");
break;
case 2:
Console.WriteLine("Two");
break;
}
//outputs Two, because it matches the variable being passed through the cases. If there was a third case, it would be voided

int age = 34;
switch(age)
{
case 6:
Console.WriteLine("Too Young");
break;
case 50:
Console.WriteLine("Too Old");
break;
default:
Console.WriteLine("The default case");
break;
}
//outputs The default case

int x = 4;
switch(x){
case 1:
Console.WriteLine("Value is 1);
break;
case 4
Console.WriteLine("Value is 4");
break;
}
//outputs Value is 4

int x= 34;
switch(x)
{
case 6:
Console.WriteLine("Value is 6");
break;
case 50:
Console.WriteLine("Value is 50");
break;
default:
Console.WriteLine("The default case");
break;
}
//outputs The default case

string light = "green";
switch(light){
case "green":
print("The light is green");
break;
case "yellow":
print("The light is yellow");
break;
}
//outputs The light is green

float x = 0.0f;
switch(x){
case 0.0f:
print("The light is green");
break;
case 1.1f:
print("The light is yellow");
break;
default:
print("The light is red");
break;
}
//outputs The light is green

float x = 0.0f;
switch(x){
case 1.0f:
print("The light is green");
break;
case 1.1f:
print("The light is yellow");
break;
default:
print("The light is red");
break;
}
//outputs The light is red

int x = 86;
switch(x){
case 43:
print("The light is green");
break;
case 86:
print("The light is yellow");
break;
default:
print("The light is red");
break;
}
//outputs The light is yellow
