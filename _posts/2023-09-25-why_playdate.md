---
title:  "Why should you program for the Playdate?"
mathjax: true
layout: post
categories: media
published: false
---
<img src="/assets/playdate-photo.png" style="float: right; padding: 0px 0px 0px 50px;" width="300" height="300">

I often get asked: "Why do you program for the Playdate? You can create literally anything on PC nowadays." Let me explain.

Paralysis by analysis is a real thing when creating a game and seriously hinder productivity. For a long time I wanted to create a certain game but didn't make much progress because I constantly thought about many different things not really tied to the game itself. Some examples:
* Choice of engine
* Multiplatform support
* Target resolution
* Multiple aspect ratios
* Color palette
* Shaders
* Keyboard, mouse, controller support
* Key bindings
* Multithreaded programming
* ...

Even without any of those things game development is already difficult enough. Tools become overly complex, big beloved game engines get devoured by greedy corporations, graphics APIs (OpenGL, DirectX, Vulkan, Metal etc.) are more fragmented than ever. However, with the creation of the famous Pico-8 back in 2015 fantasy consoles started to catch fire. Fantasy consoles try to emulate the perceived simplicity of game development of times long gone by where games faced hard constraints put in place by their hardware. This certainly hits a nostalgic nerve nowadays. Constraints is really the most important advantage of fantasy consoles: While you can almost create anything on modern platforms it's actually the contraints which boost creativity and productivity, and spark the joy of programming.

And what can be better than a fantasy console? A modern, well made *real* console, in active production and coming with an open and developer friendly environment. The Playdate is a charming yellow handheld made by Panic. Its most unique features are a monochrome e-ink-like display and a mechanical crank. The specs themselves are kind of special but nothing to brag about in terms of raw numbers:

* Display: 400x240 1-bit (black & white)
* CPU: 168 MHz, 32-bit, single-threaded
* RAM: 16 MB
* Input: DPad, 2 buttons, accelerometer, crank

All of the things provided by modern platforms which I worried about for days, weeks and even months: Just gone, with the decision to program for the Playdate. Reduced to a single low-spec hardware device to program for. No more thoughts about color palettes, aspect ratios or shaders. With the few buttons available designing an input scheme takes minutes. And the CPU naturally limits the amount of stuff going on - there is no way to simply can't cram *all of it* into the compute budget. There's only enough horsepower for things that matter which limits feature creep and scope. Of course I could have just set some technical constraints for a game myself and enjoy the same benefits. But in this case I am also responsible to stay inside my own artificial constraints - with the danger of constantly redefining them and falling victim to paralysis by analysis again.

That's why I program games for Playdate console. The console and the games have a personality. It keeps game development simple. And seeing my game running on a real touchable handheld is really special in itself.

> All of the quirks of Playdate, I think, helped tremendously in attracting developers to want to make something for Playdate,” says Cabel. “If Playdate had a full-color OLED screen and a powerful 3D chip, it would take a very long time for one person to say, ‘Yeah, I’ll make a game for that.’ By going in the opposite direction of where gaming has gone lately, we return to a scale in which one person, two people, three people can make an awesome, entertaining, you know, lengthy, meaningful title, and the constraints enable that.

Learn more about the creation of the Playdate by reading either the elaborate [blog post](https://blog.panic.com/the-story-of-playdate/) or put on the [podcast episode](https://podcast.panic.com/episodes/s01e06/).