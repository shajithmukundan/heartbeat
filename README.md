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


> Open this page at [https://shajithmukundan.github.io/heartbeat/](https://shajithmukundan.github.io/heartbeat/)

## Use as Extension

This repository can be added as an **extension** in MakeCode.

* open [https://makecode.microbit.org/](https://makecode.microbit.org/)
* click on **New Project**
* click on **Extensions** under the gearwheel menu
* search for **https://github.com/shajithmukundan/heartbeat** and import

## Edit this project ![Build status badge](https://github.com/shajithmukundan/heartbeat/workflows/MakeCode/badge.svg)

To edit this repository in MakeCode.

* open [https://makecode.microbit.org/](https://makecode.microbit.org/)
* click on **Import** then click on **Import URL**
* paste **https://github.com/shajithmukundan/heartbeat** and click import

## Blocks preview

This image shows the blocks code from the last commit in master.
This image may take a few minutes to refresh.

![A rendered view of the blocks](https://github.com/shajithmukundan/heartbeat/raw/master/.github/makecode/blocks.png)

#### Metadata (used for search, rendering)

* for PXT/microbit
<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>
