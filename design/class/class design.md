Introduction
=================



Instance creating & destroying
=================

`constructor()`: Build a new instance
-----------------

* Overridable

Example:

```ts
class Example
{
    public int x;

    constructor()      { this.x = 1; }
    constructor(int x) { this.x = x; }
}
```

Notice:

`constructor` is also a function.
The following example shows the legal usage of `constructor`.

```ts
Example  x = new Example();
Example  y = new Example.constructor(100);
function z = Example.constructor;
```


`destructor()`: Delete an exsited instance
-----------------

* Cannot override, because `delete` does not have parameters

```ts
class Example
{
    public int x;

    destructor()
    {
        delete this.x;
        notifyOthers();
    }
}
```

In-code instance creation
-----------------

Original Cesno use this way to create an instance:

1. Create in `stack`

```ts
Example x = Example();
```

2. Create in `heap`
   
```ts
Example x = new Example();
```

Overload operator in object
=================