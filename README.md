Randomize
=========

IEnumerable Randomize extension methods

A tiny class that is simple to use. Compile and include in your project and two new methods will become available on objects declared as IEnumerable<T>.

There are two methods:
1. Randomize
var list = new List<string>();
...
foreach(var element in list.Randomize())
{
  ...spits out elements randomly
}

2. ChooseRandom
var list = new List<string>();
...
var randomElement = list.ChooseRandom(); //Chooses an element from the list at random.
