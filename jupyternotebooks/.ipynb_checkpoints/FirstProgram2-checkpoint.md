---
jupytext:
  formats: md:myst
  text_representation:
    extension: .md
    format_name: myst
kernelspec:
  display_name: C++ 20
  language: c++
  name: cpp20
---

# First C++ program.

Type the following code into the empty code window below.
Please type the code exactly as shown. 
TIP computers cannot correct your mistakes for you!! 
% {lineno-start=1 emphasize-lines="2,3"}

:::{code} cpp
:linenos: 
:emphasize-lines: 4
:label: Code1
:caption: Hello World program

#include <iostream>
int main()
{
	std :: cout << "Hello, World!\n";
	return 0;
}
:::

In @Code1 the highlighted statement is the code that the programmer actually wants implemented - everything else is ...



```{tip}
To run a code block that has been edited, select the block (mouse click inside it), then simulaneously press {kbd}`Shift` + {kbd}`Enter`. 
```


```{code-cell} c++
:tags: [mytag]
#include <iostream>
int main()
{
	std :: cout << "Hello, World!\n";
	return 0;
}
```

::::{exercise} 
:class: dropdown
:label: Exercise1
Add or remove spaces anywhere in your code and run the code again. \
Or try somthing else\
or something other

:::{solution} Exercise1 
:class: hint dropdown
:label: Solution1

1. answer 1
2. answer 2
- list q
- list b
:::
::::


::::{exercise} 
:class: dropdown
:label: Exercise1
Add or remove spaces anywhere in your code and run the code again. \
Or try somthing else\
or something other

:::{solution} Exercise1 
:class: hint dropdown
:label: Solution1

1. answer 1
2. answer 2
- list q
- list b
:::
::::
````{admonition} Exercise
:class: dropdown tip
Add or remove spaces anywhere in your code and run the code again. \
Or try somthing else\
or something other

```{admonition} Solutions 
:class: dropdown hint
1. answer 1
2. answer 2
- list q
- list b
```
````
