
HW2: Time for a Time Out!
#########################


Basic measurement units:
========================

    "-" 1 meter = <**39.370**> inches (http://www.onlineconversion.com/length_common.htm)

    - 1 mile = <**5280**> feet 
      
    - 1 mile = <**1609**> meters

    - Circumference of the Earth = <**24,901**> miles (www.google.com)


Basic terminology
=================

We prefix numbers in the world of science with some basic terms. Determine what
these mean: 

    * `yotta` something = <**100000000000000000000000**> times something (https://en.wikipedia.org/wiki/Yotta-)
    
    * `kilo` something = <**1000**> times something

    * <**hecto**> something = 100 times something
    
    * <**deca**> something = 10 times something

    * `milli` something = 1/<**1000**> of something

    * `micro` something = 1/<**1000000**> of something

    * `nano` something = 1/<**1000000000**> of something

    * <**pico**>something = 1/1000000000000 of something

From Physics
============

* What is the speed of light 
  
    * = <**186,000**> mps (miles per second)(https://en.wikipedia.org/wiki/Speed_of_light)

    * = <**299,792**> kps (kilometers per second)

Speed of Electronic Signals
===========================

Assuming electronic waves move through wire at the speed of light:

* How far an electronic signal can move through a wire:

    * In one nanosecond = <??> inches (299,792*1/1000000000*

    * In one microsecond = <??> feet

    * In one millisecond = <??> miles
    
    * In one second = <??> miles

    * In one second = <??> times around the Earth!

From our World of Processors
============================

One last piece of the puzzle. I would like to see if you can figure out how
fast a signal moves between transistors in a typical Pentium processor. To
figure that out, we need to figure out how far apart they are. We will keep
this simple.

We will look at numbers for the Intel Haswell line of processors.
Unfortunately, most manufacturers use the metric system to report how big (or
small) things are, so all of the numbers in this section will be in meters (or
smaller). 

Dig out data for the Haswell Processor. Specifically, use this version:

    * Haswell GT2 4C chip

        * Manufacturing Process = <??>nm

        * Transistor Count = <??> transistors

        * Die Size: <??>mm^2

Assuming that the chip is square, and that there are 1,400,000,000 transistors
on the chip, we can take the square-root of 1.4 billion to see how many
transistors must be on each side of the square. If the actual chip has a
surface area of 264 square millimeters, figure out how long each side is, and
using your numbers from above, figure out how long it takes for an electronic
signal to move the distance between two adjacent transistors.

    * time for a signal to move between transistors = <??> picoseconds

As a check (ballpark, at least), see if your calculations match the
manufacturer's current technology. They report their ability to squeeze
transistors together in nanometers. Are your numbers close?

..  note::

    Remember that there must be room for all the "wires", actually called
    traces, needed to move signals from one place to another. So, it might seem
    like there is plenty of room left for that, in actual fact, we are reaching
    the limits on how small we can manufacture things. That is, unless we come
    up with a new technology!

Counting up
***********

As a last bit of trivia, lets see how big a 64-bit integer really is.

The current Pentium processor uses 64-bit registers. Assuming your processor is
ticking away at a rate of 2.7 GHz, how long will it take to reach the biggest
number the counter can hold (it is 64-bits wide):

    * Time until the counter "rolls over" = <??> years

References
**********

Remember to include documentation on your sources.

What to turn in
***************

Use this guide to help you format your homework:

    * `reStructuredText Quick Start
      <http://docutils.sourceforge.net/docs/user/rst/quickstart.html>`_.

You will write this up using your programming editor of choice. Make sure your
file ends with en extension of `.rst` when you add this work to your homework
project on the class GitLab_ server.

When you have uploaded your file to the GitLab_ server, check out the file
using your web browser. It will be formatted so it looks like a nice web page.
Do not get carried away with this for now. This markup language is designed to
be simple to learn and use, and it leaves your text file readable, even without
processing. As long as the file ends with a `.rst` extension, GitLab_ will
automatically convert the page to HTML so it looks nice in your browser.

I want YOU to be proud of the quality of your work! Using good tools will help
you get to this point!

reStructuredText_ is rapidly becoming a standard in documenting software
projects. While it was originally developed to document Python language, it is
increasingly being used elsewhere. The tool most often used to process
documentation for large projects is Python Sphinx_. We will take a look at this
tool a bit later in the course.

..  vim:filetype=rst spell
