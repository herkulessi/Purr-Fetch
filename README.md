#  Purr-fetch
## A System fetching tool written in python. 
### ( and now also alternative versions written in rust and C++ by friendly contributors!! )
![](https://github.com/DeLuks2006/Purr-Fetch/blob/main/Screen-from-WSL.png)

**What is this?:** Purr-Fetch is a command-line information tool written in Python, that displays various information about your system! It's main use case is to be used in screenshots so it looks pretty but you may also just use it to get your system information. 👍

**How does it work?:** It uses python to get information about your system, like for example what shell, distro and kernel version you are using.

**NOTE:** This project is a work in progress! ⚠️

---

### How to install and use:

* clone this repository - `git clone https://github.com/DeLuks2006/Purr-Fetch.git`
* change into the cloned directory - `cd Purr-Fetch`
* run the fetch.py - `python fetch.py` OR `./fetch.py`

**for the rust (less bloated and faster) version:**
* install rustc with your package manager - `pacman -S rust` in case of Arch Linux
* clone this repo
* change into the cloned directory - `cd Purr-Fetch`
* run the fetch.rs - `./fetch.rs`

**For the C++ version:**

- Compile `fetch.cpp` with a compiler of your choice with C++11 standard or later.
  Example using `g++`: `g++ fetch.cpp -o fetch`
- Running the compiled script:
  `./fetch`

**For the Java version (more bloated and slower):**

- Install default-jre with your package manager.
- Run the fetch.java file with Java.

### Known issues:
- missing features (terminal detection) <-- idk how to do it, please be patient while I figure it out.
- missing formatting for uptime in C version

### How to contribute:

Just contribute here by fixing my bad and messy code and explaining what I did wrong. XD
**OR** you may also just add another version of the fetch in an language that is not yet featured (please leave the C version out, im going to do that one XD)
Please note that I am a beginner so I may not understand every mistake. 👍
