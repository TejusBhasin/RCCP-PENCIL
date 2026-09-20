# ChEaP-ApPlE-PeNcil_wIth-BacKworDs-ComPATABiLIty

A cheap 3D printed "Apple Pencil" that doesn't actually use Apple Pencil electronics.

## What is this?

I wanted to make a stylus for an iPad that was as simple as possible.

Instead of using a battery, Bluetooth, or any Apple Pencil electronics, this uses the fact that a touchscreen can detect conductive objects. The idea is that you hold the conductive metal, and that connection goes down to the tip.

Basically, it's a really fancy way of making a touchscreen stylus out of plastic and metal.

## Why did I make it?

I use an iPad for school and use a stylus a lot. The problem is that Apple Pencils are pretty easy to lose, break, or lose the tip for.

So I started thinking: why does a stylus even need to be complicated?

I did some research into how touchscreens and cheap passive styluses work and realized I could try making my own.

The goal was basically:

**Make something that works like a stylus without making an actual Apple Pencil.**

## How does it work?

The iPad has a capacitive touchscreen. Your body is conductive, which is why a touchscreen can detect your finger.

My idea is to use a piece of conductive metal to connect the part you're holding to the tip.

```text
        Your hand
           ↓
    Conductive metal
           ↓
      Metal tip
           ↓
       iPad screen
```

There aren't any batteries or electronics inside it.

## The 3D Printed Part

I designed the body in CAD and made a few different versions while figuring out the shape.

There's a groove around the body where the aluminum foil can go. The idea is that the foil sits there and connects the area you're holding to the tip.


## The Candy Holder

I also decided that the pencil needed a completely unnecessary feature: a candy holder.

The bottom has a little compartment for candy, with a hole that helps with air pressure when putting the candy in or taking it out.

Because apparently a stylus wasn't enough. Now it can hold a snack too.


## Assembly

The basic idea is pretty simple:

1. 3D print the body.
2. Cut a piece of aluminum foil.
3. Put the foil around the groove in the body.
4. Run it down toward the tip.
5. Make sure the foil makes a continuous connection to the tip.
6. Put some candy in the holder if you want.
7. Try it on an iPad.

The exact assembly may change as I test different versions.

## Files

I've included the files so other people can actually use and modify the project.

```text
/
├── CAD/
│   └── Editable CAD files
├── STL/
│   └── Files for 3D printing
└── README.md
```

The CAD files are included because an STL by itself isn't very useful if someone wants to change the design.


## What I Learned

The biggest thing I learned was how capacitive touchscreens actually work.

At first I was thinking about making something that somehow copied the signals from an Apple Pencil. After researching it, I realized that I could approach the problem from the other direction and just use the same basic principle as a passive stylus.

I also went through a few CAD iterations while figuring out where the conductive material should go and how the candy compartment would work.

## Current Status

The CAD design is mostly finished and I've made several iterations of it.

The design currently has:

* 3D printed body
* Conductive metal path
* Conductive tip
* Candy holder
* Air-pressure hole
* Editable CAD files
* Printable STL files

I'm still working on physical testing and seeing how well the design actually works.

## Future Ideas

If I keep working on it, I'd like to try:

* Different conductive materials
* A better tip
* A replaceable tip
* Making the grip feel better
* More candy-holder designs
* Making the whole thing smaller
* Testing different shapes

## Made By

**Tejus Bhasin**

Made for Hack Club Forge.
