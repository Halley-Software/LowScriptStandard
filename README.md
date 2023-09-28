# LowScript Standard
In this repository u have a guide of how develop LowScript, it is designed to help LowScript developers understand about how it works internally.</br>

From this standard, you should be capable to recreate a LowScript in your own way.
There are not a specific way of how LowScript is created, how many lines must have a LowScript compiler or what lib you use to manage the event loops.

So, you are free of design your own LowScript compiler, and it will be called LowScript as long as you follow the language specification, rely on the software you design, you can make LowScript more or less efficient, powerful or another hundreds of adjectives that exists.</br>
Even you can recreate LowScript with LowScript himself!

## Example
Take as example, JavaScript, his standard is specified in [ECMA-262 Specification](https://tc39.es/ecma262/). If u follow this standard, you will recreate JavaScript, but there are not a specific way of own design it.</br>

## Conclusion
So if u think that u can make better LowScript, you can follow this standard to create your own compiler. I tried to make it the most understandable I could using images and code examples.</br>

In another way If u think that you have an idea that can fit with LowScript, exists the posibility of give us your idea, if it is a good idea, we can implement it in the official standard!

# ---- Standard ----

## Standard library
LowScript have an standard library that offers differents utilities for differents purposes, make net connections, read files, generate UUID, manage JSON data, etc...</br>

The utilities that LowScript should implements are:
  - net - (Net connections)
  - io - (data manipulations)
    - Read file(s)
    - Write file(s)
    - Create file(s)
    - Delete file(s)
    - Encrypt streams (file(s), stream(s))
  - thread - (Threads manipulation)
  - zip - (ZIP compression manipulation)
    - Compress file(s)
    - Decompress file(s)
  - http - (HTTP implementation)
  - os - (OS manipulation and OS characteristic)
  - time - (Time manipulation)
  - stream - (Stream(s) manipulation)
  - path - (Path(s) manipulation)
  - uuid - (UUID generation and manipulation)
