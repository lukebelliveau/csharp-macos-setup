# C# Environment Setup on Mac
Setting up dev environment for C# dev on Mac. Guide for peers on a client project. Not much to see here!

## Install Mono
Download and install Mono [here](http://www.mono-project.com/). In their words, Mono is *an open source implementation of Microsoft's .NET Framework based on the ECMA standards for C# and the Common Language Runtime*. For us, that means you get to compile .cs files, build solutions, and run executables compiled from C# source.

You can verify this works by running one of your new commands, like `csc` or `msbuild` in your shell. If the command exists (it'll complain about `No source files specified` or the like), you're good.

## Install Rider
Drink more JetBrains kool-aid.  Download and install Rider from [here](https://www.jetbrains.com/rider/). You'll get a 30 day free trial, but you should ask our employer for a license.

## Run it
Create a new console application in Rider:
![New Solution](https://image.ibb.co/k7ZVFb/Screen_Shot_2017_10_05_at_11_47_57_AM.png)

![Create console app](https://image.ibb.co/cPOJ1G/Screen_Shot_2017_10_05_at_11_48_11_AM.png)


Set up your run configuration:
![Edit Configurations](https://image.ibb.co/mf5y1G/Screen_Shot_2017_10_05_at_11_53_00_AM.png)

![Setup](https://image.ibb.co/cqbGow/Screen_Shot_2017_10_05_at_11_52_47_AM.png)

Run it!
![Run](https://image.ibb.co/ciqqgG/Screen_Shot_2017_10_05_at_11_52_21_AM.png)

You can also compile and run it through the command line with Mono:
![Mono](https://image.ibb.co/kSgKab/Screen_Shot_2017_10_05_at_11_58_49_AM.png)
