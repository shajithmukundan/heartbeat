# tutorial
# Heart Beat tutorial

## Step 1

In this project we use the ``||basic: show leds||`` block to create a heart beat 

## Step 2

Pick one ``||basic: show leds||`` and snap it inside the ``||basic: forever||`` block

```block
basic.forever(function () {
basic.showLeds(`
        . . . . .
        . . . . .
        . . . . .
        . . . . .
        . . . . .
        `)


}

```

## Step 3

Now add two more ``||basic: show leds||`` inside the ``||basic: forever||`` block 

```block
basic.forever(function () {
basic.showLeds(`
        . . . . .
        . . . . .
        . . . . .
        . . . . .
        . . . . .
        `)

basic.showLeds(`
        . . . . .
        . . . . .
        . . . . .
        . . . . .
        . . . . .
        `)

basic.showLeds(`
        . . . . .
        . . . . .
        . . . . .
        . . . . .
        . . . . .
        `)


}

```   

## Step 4

Now, fill the 3 ``||basic:showLeds||`` block with this pattern  

```block
basic.forever(function () {
basic.showLeds(`
        . . . . .
        . # . # .
        . # # # .
        . . # . .
        . . . . .
        `)

basic.showLeds(`
        . # . # .
        # . # . #
        # . . . #
        . # . # .
        . . # . .
        `)

basic.showLeds(`
        . # . # .
        # # # # #
        # # # # #
        . # # # .
        . . # . .
        `)


}

``` 

## Step 5

Now you can run the code on the Simlulator and check how it works