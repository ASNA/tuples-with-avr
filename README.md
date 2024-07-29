## This repo shows how to use .NET Framework's System.Tuple class with AVR

See comments in the code. 

Briefly, it's very easy to use Tuples with AVR: 

```
// Instance a new Tuple. Tuples are immutable (their values can't 
// change). This return value will be read-only to its consumer.
LeaveSr *New Tuple(*Of *String, System.Decimal)(Name, Rate)  
```

Tuples are handy when you want to return multiple values from a function. 

You can also return a class instance from a function which is also a good way to to return multiple values from a function. 






