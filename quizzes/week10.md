# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
This allows you to put things into an import so everything is importated everywhere that namespace is.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
structs are value type and class is a reference type.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
i think this is void
```
## Example 1
```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```
**5.** In the example what is the access modifier of the `Start()` method?
<!-- enter you answer in the space below -->
```
public
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
It is what that function returns
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
It prevents start from being inherited
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
a virtual is to be inherited by children classes
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
private public internal and protected
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
only the class that it is in can access it.
```