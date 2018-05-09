simple live coding
===============

This is a proof of concept for a live drawing app in Ruby with
the [JRubyArt Gem (based on processing-3.3.7, and jruby-9.1.17.0)](https://github.com/ruby-processing/JRubyArt) java version openjdk version "1.8.0_172"


Get inspired by [Bret Victor](http://worrydream.com/#!/LearnableProgramming) or join the project with your own idea..

![drawing from a 6 year old girl](http://i43.tinypic.com/15n8x9v.jpg)
This drawing was made from a 6 year old girl at the CoderDojo cologne...

There is a stand alone app to play with without need of installing all stuff.
With "ellipse 50, 50, 80, 80" or "rect/line/fill" you can draw and with mouse dragging change the values.


Notice
===============

Start JRubyArt with `k9 -w simple_live_coding.rb`. This reloads `simple_live_coding.rb` after saving and you can implement your ideas in this file
without need to restart. After implementation of the new feature just copy your code in a seperate file in the "main" directory and do "require_relative" for the file.

This is a live coding app...
