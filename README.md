LEDDisplay
==========

TheGeekKid's addition:
This addition allows the user to pull the current threat level from https://msisac.cisecurity.org/alert-level/ and display it on the display.

This project was created by FuzzyWuzzie - many thanks for making this easier than I thought it was going to be.  The original description is below:

A C# program made for displaying useful data (unread email count, weather, and time currently) on the [Dream Cheeky LED Message Board](http://www.dreamcheeky.com/led-message-board)

## What It Does

It scrolls real-time information across the Dream Cheeky LED Message Board display. It currently only tells the current time, the weather, and how many unread emails I have in my inbox. With your help, it can easily do more. Here's a video of it in action:

[![YouTube video of program in action](http://i.imgur.com/bKZIcE3.png)](https://www.youtube.com/watch?v=xlyV3vIF-xE)

## How To Use

1. Compile the program with Microsoft Visual Studio. You might have to deal with a dependency for [mikeobrien/HidLibrary](https://github.com/mikeobrien/HidLibrary) but it should be relatively easy to sort out. I've included a pre-built DLL here for you to use in case you can't figure it out.
2. In the `LEDDisplay.exe.config` file that gets produced alongside the executable, change `YOUR_GMAIL_USER_NAME_HERE` to your GMail username. Similarly, change `YOUR_APPLICATION_PASSWORD_HERE` to a [Google application-specific password](https://accounts.google.com/b/0/IssuedAuthSubTokens?hl=en&hide_authsub=1) that you set up ahead of time. To change the weather location, change `Edmonton,AB,Canada` to wherever you live. You can also change the weather units to imperial if you don't like metric.
3. Make sure your Dream Cheeky LED Message Board is plugged in and working (test it with Dream Cheeky's program, then make sure their program is closed).
4. Launch LEDDisplay.exe
5. An LED icon will show up in your taskbar, use it to control what is currently being displayed.
6. Hack it! Pull requests and forks aren't just welcome, they're encouraged! I think this is a good piece of hardware that is rendered almost useless by it's default software. Fortunately, we can do better!
