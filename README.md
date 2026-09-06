# Herse

Herse is a lightweight and expressive programming language that compiles to readable Lua.

## Features that make it different from Lua
 - Static typing capabilities
 - User-Friendly syntax
 - OOP features
 - Macros

## Warning
This is not a finished nor serious project, and was mostly just made out of boredom. This has a chance to become a serious project in the future, but that is still unlikely.

## Requirements
- Lua 5.1 or later

## Installation
Clone this repo and optionally add it to your $PATH.

## Usage

Compile a Herse file to a Lua file with the same name:

```console
hrc path/file.hrs
```
This creates:

```text
path/file.lua
```

To print the compiled Lua to standard output instead:

```console
hrc-out path/file.hrs
```

Run a Herse program directly with:

```console
hrs path/file.hrs
```

## Code Examples
A bunch of code exaples with comments are available in ./code, check them out!

## Fun Facts
 - Herse is one of Jupiter's moons
 - This language was originally called Charon before I found out that name was taken
 - The first working version of this transpiler was made in under 5 hours (all the features it had are used in ./code/main.hrs)
 - I don't have any more fun facts
