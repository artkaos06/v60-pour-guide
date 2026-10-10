# V60 Pour Guide

A step-by-step V60 brew guide driven by live weight from a Bluetooth scale (KP2048B "MY_SCALE", the protocol GaggiMate uses).

Open https://artkaos06.github.io/v60-pour-guide/ in Chrome on Android or a computer, press **Connect scale**, pick `MY_SCALE`, choose a recipe and roast, then press **Start**. The timer starts when water hits the scale.

Recipes include Hoffmann, Kasuya 4:6 and its variations, Rao, an iced V60 and more.

Built for the KP2048B Smart Kitchen Scale.

## Recipes

Recipes live in `recipes.json`. Each pour target is a fraction of the total water (`to`) or a multiple of the coffee dose (`toDose`); `by` and `until` are seconds from the first pour. Send Claude a recipe link to add one.
