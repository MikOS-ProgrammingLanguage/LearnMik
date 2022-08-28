# **3.0 Variables in Mik**

Variables in mik are statically typed, i.e.the type of a variable can and will not be inferred, and must be explicitly written in a declaration. Mik also supports pointers (which i will discuss later on in this chapter)

## **3.1 The typing system, and how to declare variables**

In mik the basic declaration of any variable looks like this:

    <variable behavior descriptor> <type descriptors> <type> name

a variable can also be assigned a value lik so:

    int foo = 10

but can also be just a declaration, which looks like this:

    int bar

you can find a compendium of all types [here](sources.md#full-compendium-of-base-types)

<br>

> **Note**, however, that a declaration (int bar) has no value by default. Hence, referencing this variable will lead to the variable having "memory garbage as it's value".

<br>

## **3.2 What are variable behavior descriptors and type descriptors?**

Now that we know how variables are declared what are those variable behavior descriptors, and type descriptors that i briefly mentioned?

### **3.2.1 Variable behavior descriptors**

Variable behavior descriptors define the property of a variable, i.e. they define the behavior of said variable.

An example of such variable behavior descriptor would be

    global int my_int = 10

where global defines the behavior of the variable. 

> Note: You can also find a full compendium of all variable behavior descriptors [here](sources.md#full-compendium-of-variable-behavior-descriptors)

### **3.2.2 Type descriptors**

Type descriptors specify additional information about a variable. To fully understand that let's look at an example:

    long int li = 100

The type here is ``int``. Not ``long int``. ``long`` is just ***describing*** the type int to be an integer, which is long.

> Note: Once again you can find a full compendium of all type descriptors [here](sources.md#full-compendium-of-type-descriptors)

## **3.3 Bringing it all together**

Using all the information gathered in [3.1](03-variables.md#31-the-typing-system-and-how-to-declare-variables),  and [3.2](03-variables.md#32-what-are-variable-behavior-descriptors-and-type-descriptors), what would a variable of the name foo look like, that is of type integer, which is long and also global holding the value 0xBEEF? (Click below if you think you know the answer)

<details>
  <summary>Solution</summary>

    global long int foo = 0xBEEF

</details>

Correct? Great! If you are a bit more experienced in programming or down for the Challenge you can also read the [next Chapter](04-pointers.md#pointers) about pointers. **But it's not mandatory!**
