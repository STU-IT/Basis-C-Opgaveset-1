# Basis C, Opgaveset 1
Det første set af opgaver til C

## Opgave 1 - Itsa Mario

Toward the end of World 1-1 in Nintendo’s Super Mario Brothers, Mario must ascend a "half-pyramid" of blocks before leaping (if he `wants to maximize his score) toward a flag pole. Below is a screenshot.

!(img/mario.png)

Write, in a file called `mario.c` in your `~/Basis-C-Opgaveset-1` directory, a program that recreates this half-pyramid using hashes (`#`) for blocks. However, to make things more interesting, first prompt the user for the half-pyramid’s height, a non-negative integer no greater than `23`. (The height of the half-pyramid pictured above happens to be `8`.) If the user fails to provide a non-negative integer no greater than `23`, you should re-prompt for the same again. Then, generate (with the help of `printf` and one or more loops) the desired half-pyramid. Take care to align the bottom-left corner of your half-pyramid with the left-hand edge of your terminal window, as in the sample output below, wherein underlined text represents some user’s input.

```
jharvard@appliance (~/Basis-C-Opgaveset-1): ./mario
height: 8
       ##
      ###
     ####
    #####
   ######
  #######
 ########
#########
```

Note that the rightmost two columns of blocks must be of the same height. No need to generate the pipe, clouds, numbers, text, or Mario himself.

By contrast, if the user fails to provide a non-negative integer no greater than 23, your program’s output should instead resemble the below, wherein underlined text again represents some user’s input. (Recall that GetInt will handle some, but not all, re-prompting for you.)

```
jharvard@appliance (~/Basis-C-Opgaveset-1): ./mario
Height: -2
Height: -1
Height: foo
Retry: bar
Retry: 1
##
```

To compile your program, remember that you can execute

```
make mario
```

or, more manually,

```
clang -o mario mario.c -lcs50
```

after which you can run your program with the below.

```
./mario
```
###Problems
Not sure where to begin? Not to worry. A walkthrough awaits!

[Walktrough video on YouTube](https://youtu.be/z32BxNe2Sfc)



_**Der kommer mere...**_
