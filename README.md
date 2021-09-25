# AnthonysAwesomeArithmeticLibrary
Reusable library of basic arithmetic functions written in C#.

Measures to make library reusable:  
-Public methods heavily documented, which describes to user what each method does in detail. Makes it easier for potential users to understand.  
-Static class/methods allow library to be invoked without need for creating instances of class. Static methods can be accessed directly in static and non-static methods.   Conceptually, this makes sense for a Math Library, and actually is how the Math library in C# is implemented, as you don't really need/want separate instances.  
-Project is in source control and public. This allows anyone to be able to access the code, and allows for project to easily get updates, and allows for collaboration amongst   other developers.  
-Methods are made simple: simple, to the point naming, and functionality kept basic. Left open to extension later on: potentially adding more in depth error handling as an example, or handling specific cases that may not be covered (negative numbers in certain areas).  
  
# How To Run Project
You will need Visual Studio 2017 or 2019 with installed NUnit Runner extension. No real newer language features of C# are added, however, it is a netcore 3.1 app, so .NET Core 3.1 will need to be downloaded to run.
