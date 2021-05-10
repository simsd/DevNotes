# CS 144 FrontEnd + TypeScript

#### By Simran Singh Dhaliwal UCLA Spring 2021



## Client-Side Framework

Simple programs will become hard to maintain once as you start adding more to it, these is where frameworks enter the picture. The challenges we want to solve are:

1. code complexity
2. lack of modularity 
3. code resuability 

 Applications are typically split into similar parts named **components**, we want our development to develop a heirachy  of these components

## Type Script

basically javascript with more versions, anything in javascript is typescript code (superset).  All additional features are **optional**. 

```typescript
//this is the javascript code
function hello(name)
{
    return ("hello" + name)
}

hello("Simran")


//typescript, passing in string and returning a string
function hello(name : string) : string
{
    let world: string = "name";
    return ("hello, " + name + "!")
}
```



```shell
//Compiling TypeScript to Javascript
//No browsers use typescript

npm install -g typescript
tsc hello.ts //will give the hello.js file!!!
node hello.js
```

The value of typescript is that its rigidity makes it ==fail at complie type rather than runtime==(aka static type checking), additionally we can now overload functions!!

There are mutlipe different types in TS:

1. number
2. string 
3. boolean
4. number[]
5. [number, string] this is a tuple
6. (number | string) can take number OR string

### Decorators 

* can be added to declarations to modify entities like @sealed will stop changes to the structure of an objects

Also there are constructors, interfaces, and templates but these are also present in languages like C++ and Java so I will not be diving deep into them

































