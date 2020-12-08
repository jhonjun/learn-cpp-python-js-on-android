# learn-cpp-python-js-on-android
You're a student on a really tight budget. You don't have a PC or Mac but you have a fairly decent Android phone or tablet. You want to learn programming offline. Look no further, this post is for you!

This will help you setup an environment where you can try programming in C, C++, Python or Node.js on Android. First, you would need to install an app called Termux. For this, you will need to connect to the internet via your WiFi in school, with a friend or mobile data.

Go to Google Play Store, find and install Termux by Fredrik Fornwall.

https://play.google.com/store/apps/details?id=com.termux&hl=en_SG&gl=US

After installing, press Open to run. The app will show a terminal and ready to accept commands on the $ prompt.

## Do an update

```
$ apt update
$ apt upgrade
```

## Install Node.js

```
$ apt install nodejs-lts
```

## Install Python (includes Clang, a drop-in replacement for GCC C/C++ compiler)

```
$ apt install Python
```

You will need an editor to do your coding. You can use either nano or vim. Nano is installed by default. To install vim, do:

```
$ apt install vim
```

Note: edit your sample hello program(s) using your preferred editor.

## C

You can compile your C program using GCC:

```
$ gcc -o hello hello.c
$ ./hello
```

## C++

Compile and run your C++ program:

```
$ g++ -o hello_cpp hello.cpp
$ ./hello_cpp
```

## Python

Run your Python script.

```
$ python hello.py
```

## Node.js

Run your Node.js program.

```
$ node hello.js
```

You now have C, C++, Python and Node.js to play with even if you're offline. Good luck and wish you all the best in your programming journey!
