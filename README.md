# For Loops Intro

This is an introduction to some basic `for` loops.

Here is a complete `for` loop:

```cs
for ( int i = 1; i <= 50; i++ )
{
    // Code here
}
```

We can see that the `for` loop is broken down into 3 distinct statements.

+ Firstly is the `Initialise` stage:

```cs
int i = 1;
```

In the code above, we create a variable called `i`. This variable will be the _counter_ of our loops.

+ Secondly is the `Condition` stage:

```cs
i <= 50;
```

This part of the code checks if the statement is true. If it is true, then the code will loop again. If the code is false, it will stop looping.

+ Thirdly is the `Incrementing` stage:

```cs
i++;
```

This part of the code is responsible for _incrementing_ the variable, `i`.

This means that every loop of the code, `i` will increase by one.

<br>

Everything inside the `{ }` of the code will run until the _condition_ is false.

Take this piece of code as an example:

```cs
Console.WriteLine(i);
```

<details>
    <summary>
        If the above code was placed inside the for loop, what would the result be?
    </summary>

    1 2 3 4 5 6 7 .. 50

</details>

<br>
<br>

**_Now lets look at the other loop._**

This is what the other `for` loop looks like:

```cs
for ( int i = 50; i > 0; i --) {
    // Code here
}
```

This type of loop follows the same rules as the loop above.

However, this loop counts down instead of up: 

+ In the `Iteration` stage, instead of starting at one, we start at 50.

```cs
int i = 50;
```

+ In the `Condition` stage, we check if the _iterator_ is larger than 0. If it is, then we keep looping.

```cs
i > 0;
```

+ In the `Incrementing` stage, instead of counting up, (`i++`), we count down.

```cs
i--;
```

Look at the following code:

```cs
Console.WriteLine(i);
```

<details>
    <summary>
        If the above code was placed inside the for loop, what would the result be?
    </summary>

    50 49 48 47 .. 1

</details>

<br>

Learn more about loops [here](https://github.com/fslcoding/Loops).