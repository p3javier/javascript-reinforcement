# JavaScript reinforcement class



## Section 1: Setting Up Your Environment

Note: This will only appear in the speaker notes window.


## There are few options

- **Locally**: VSCode (preferred for the realwork)
- **Web**: Gitpod (good for learning)
- **Playground**: Codepen, Codesandbox, JSFidle, etc (good for testing snippets of code)


## Setup local environment

**Code editor ➡️** VSCode + plugins + theme + coding font (Fira Code + ligatures) [create a link to your config]
           
**➕**

**(Node + NPM) ➡️** I recommend install them via [NVM](https://github.com/nvm-sh/nvm)



## Section 2: JS Basics

![JavaScript Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/6/6a/JavaScript-logo.png/240px-JavaScript-logo.png)

<sup> **Note for students:** For the basics we can use simply [Codepen](https://codepen.io/p3javier/pen/gOKrxpe?editors=0012) to test our code.</sup>


## Definition

JS is a cross-platform, object-oriented scripting language used to make webpages interactive (though nowadays it has extended to other domains).


## A bit of history

- Invented in 1995 by **Brendan Eich** while working at NetScape, precursor company of Mozilla Foundation.

- Nowadays is standarized by **ECMA International** ( acronym for European Computer Manufacturers Association).

- The standarized version  is called **ECMAScript** or ES for short. And is actually in what developers program,colloquially people refer to as JavaScript or JS.


### Identifying the atoms

- Variables
- Data Types
- Comments
- Operators
- Conditionals
- Functions
- Events



## The atoms 

# ⚛️


### Variables 🔣

Variables are containers that store values. 

```javascript
let myVariable;
```

<p class="fragment">⬆️ This is a vairable declaration example</p>

<p class="fragment">Variables can be declared using 3 different keywords: <code class="fragment">var</code>, <code class="fragment">let</code> <span class="fragment">and <code>const</code></span></p>


<p class="fragment"><code>var</code> Declares a variable, optionally initializing it to a value.</p>

<p class="fragment"><code>let</code> Declares a block-scoped, local variable, optionally initializing it to a value.</p>

<p class="fragment"><code>const</code> Declares a block-scoped, read-only named constant.</p>


This is a block of code:

```javascript
{
    let apples = 0;
    apples += 1;
}

```

<p class="fragment">In JS is basically any statement between curly braces <code>{}</code></p>


A semicolon `;` at the end of a line indicates where a statement ends. It is only required when you need to separate statements on a single line. However, some people believe it's best practice to have semicolons at the end of each statement.



## Data Types


The latest ECMAScript standard defines eight data types:


- Seven data types that are primitives:

    1. Boolean. true and false.
    2. null. A special keyword denoting a null value.
    3. undefined. A top-level property whose value is not defined.
    4. Number. An integer or floating point number. For example: 42 or 3.14159.
    5. BigInt. An integer with arbitrary precision. For example: 9007199254740992n.
    6. String. A sequence of characters that represent a text value. For example: "Howdy".
    7. Symbol. A data type whose instances are unique and immutable.


- and Object



## Functions `\[ f(x) = x \]`


A function is a code snippet that can be called by other code or by itself, or a variable that refers to the function.