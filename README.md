## TypeScript – Overview
Hello! My name is Boris Kobzarev, I am a The Rolling Scopes School student and this is my presentation about TypeScript.

## What is TypeScript?
By definition, “TypeScript is JavaScript for application-scale development.”

TypeScript is a strongly typed, object oriented, compiled language. It was designed by Anders Hejlsberg (designer of C#) at Microsoft. TypeScript is both a language and a set of tools. TypeScript is a typed superset of JavaScript compiled to JavaScript. In other words, TypeScript is JavaScript plus some additional features.

On the slide you can see how quickly the popularity of the language is growing. In just two years, the number of satisfied users has doubled.

## Why Use TypeScript?
 **Code easier to understand**
Usually when you work on a piece of code, for example a function code, to understand it fully you need to grasp:

- What arguments does it accept?
- What value does it return?
- What external data does it require?

In dynamically typed languages, very often it is difficult to answer the questions. In statically typed languages like TypeScript, you get answers to all of the above questions immediately from your IDE and compiler. No longer you need to look through entire code base, keep bugging your workmates with questions, or risk having bugs on production.

**Code easier to refactor**
There’s often quite a lot of things you would like to refactor, but because they touch so many things and files, you’re just too afraid of changing them.
In TypeScript, such things can often be refactored with just one click of “Rename Symbol” command in your IDE.
In dynamically typed languages, the best thing you can get to help you with refactoring multiple files at the same time is Search & Replace with RegExp.
In statically typed languages, Search & Replace isn’t that needed anymore. With IDE commands like “Find All Occurrences” and “Rename Symbol”, you can see all occurrences in the app of the given function, class, or property of an object interface.

**Less bugs**
Typescript does not allow you do a typo, use a value that might be null, or pass an object into a place where it should be an array instead.
It is now way more difficult to write invalid code. If it compiles, you might be quite sure that it actually works.

**Less boilerplate tests**
When you are sure your variables are passed correctly into all given places, you don’t need to test all of it that much anymore.
Less tests means shorter time to develop new features, and a smaller codebase, which in turn is less complicated, less error-prone and easier to maintain.

**Aids the developer in having the correct workflow**
When writing code in statically typed languages, you first need to think about the types of the data you’ll receive, and then about the type of data you want to produce. Usually only after that you sit down to the actual implementation.
For example, whenever you develop an algorithm, you should first think about its’ theoretical formula, and then implement it.
Same thing applies to TypeScript. It encourages you to think about the interface of your code before sitting down to its’ internal implementation.

## TypeScript and ECMAScript
The ECMAScript specification is a standardized specification of a scripting language. There are ten editions of ECMA-262 published. TypeScript is aligned with all of the ECMAScripts specifications.
TypeScript adopts its basic language features from the ECMAScript5 specification, the official specification for JavaScript. TypeScript language features like Modules and class-based orientation are in line with the EcmaScript 6 specification. Additionally, TypeScript also embraces features like generics and type annotations that aren’t a part of the EcmaScript6 specification.

## Features of TypeScript
- **TypeScript supports other JS libraries.** Compiled TypeScript can be consumed from any JavaScript code. TypeScript-generated JavaScript can reuse all of the existing JavaScript frameworks, tools, and libraries.
- **TypeScript is portable.** TypeScript is portable across browsers, devices, and operating systems. It can run on any environment that JavaScript runs on. Unlike its counterparts, TypeScript doesn’t need a dedicated VM or a specific runtime environment to execute.
- **TypeScript is Object-Oriented language:** TypeScript provides a complete feature of an object-oriented programming language such as classes, interfaces, inheritance, modules, etc. In TypeScript, we can write code for both client-side as well as server-side development.
- **TypeScript is just JavaScript.** TypeScript starts with JavaScript and ends with JavaScript. Typescript adopts the basic building blocks of your program from JavaScript. Hence, you only need to know JavaScript to use TypeScript. All TypeScript code is converted into its JavaScript equivalent for the purpose of execution.

## Components of TypeScript
At its heart, TypeScript has the following three components:
-	Language − It comprises of the syntax, keywords, and type annotations.
-	The TypeScript Compiler − The TypeScript compiler (tsc) converts the instructions written in TypeScript to its JavaScript equivalent.
-	The TypeScript Language Service − The "Language Service" exposes an additional layer around the core compiler pipeline that are editor-like applications. The language service supports the common set of a typical editor operations like statement completions, signature help, code formatting and outlining, colorization, etc.

When a TypeScript script gets compiled, there is an option to generate a declaration file (with the extension .d.ts) that functions as an interface to the components in the compiled JavaScript. The concept of declaration files is analogous to the concept of header files found in C/C++. The declaration files (files with .d.ts extension) provide intellisense for types, function calls, and variable support for JavaScript libraries like jQuery, MooTools, etc.
