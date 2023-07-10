# LOTUS, a Corne (crkbd) Keymap

> The Corne keyboard is a split keyboard with 3x6 column staggered keys and 3 thumb keys, based on Helix. Crkbd stands for Corne Keyboard.
> [Foostan](https://github.com/foostan/crkbd)

## Intro

// add spicy image

I bought this keyboard from [BeeKeeb](https://shop.beekeeb.com/) with a soldering service, since I sometimes tend to overheat some pcbs..

A summary of features that I have changed in the firmware:

| General detail | Description |
|----------------|-------------|
| 7 Total Layers | :) too lazy to describe. see below |
| OLED print orientation | `270deg` on main display, and the other is rotated to `180deg` |
| heavily customized `glcdfont` | Logos, Font and indicators have been changed / removed |
| RGB uwu | enabled / disabled some RGB modules |

This is my first split keyboard. :) So I'm still learning.

## Specs

I have the following hardware: (totally unsorted)

| Component | Quantity |
|-----------|----------|
| [Sea-Micro](https://github.com/joshajohnson/sea-micro) (I believe..) | 2 |
| 128x32 OLED screen | 2 |
| fancy TRRS cable | 1 |
| Corne PCB | 1 set |
| Carbon top plate | 1 set |
| Carbon bottom plate | 1 set |
| Kailh Purpz Choc | 42 |
| MBK Glow Keycaps | 1 set |

## How do I compile this?

1. Install [QMK](https://docs.qmk.fm/#/newbs) and git
2. do a `git clone git@github.com:qmk/qmk_firmware.git ~/qmk_firmware`
3. then do a `git clone git@github.com:74k1/crkbd_firmware.git ~/qmk_firmware/keyboards/crkbd/keymaps/74k1`
4. now you should be able to do a simple: `qmk compile -kb crkbd -km 74k1`
5. then flash it with the 

## Layers

Purple / Pink : holding

Green : tapped

### Default Layer

![default](assets/layer%20default.png)

### Layer 1 

![1](assets/layer%201.png)

### Layer 2 

![2](assets/layer%202.png)

### Layer 3 

![3](assets/layer%203.png)

### Layer 4 

![4](assets/layer%204.png)

### Layer 5 

![5](assets/layer%205.png)

### Layer 6 

![6](assets/layer%206.png)

## glcdfont

// add spicy image

## Credits

| Name | Remarks |
|------|---------|
| [foostan](https://github.com/foostan/crkbd) | For making the keyboard |
| [joric](https://github.com/joric/qle) | For the `glcdfont` editor and having the import / export image feature |
| [Leo from BeeKeeb](https://store.beekeeb.com/) | For the assembly and overall very good service. |
| [laosteven](https://github.com/laosteven/fluffy-octo-eureka) | For giving me this repo Idea. |
