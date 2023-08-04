# Steffi <!-- omit from toc -->

Steffi is a pair of highly-optimized transpilers.
* `steffi1.rs` is a transpiler from Rust to CrabLang, written in Rust.
* `steffi2.rs` is a transpiler from CrabLang to Rust, written in CrabLang.

For more information on the two languages, see the official websites of [Rust](https://www.rust-lang.org/) and [CrabLang](https://crablang.org/).

## FAQ <!-- omit from toc -->
- [How do I run the transpilers?](#how-do-i-run-the-transpilers)
- [I did not supply any file names to Steffi? How does Steffi know which files to transpile?](#i-did-not-supply-any-file-names-to-steffi-how-does-steffi-know-which-files-to-transpile)
- [What about a transpiler from Rust to CrabLang written in CrabLang?](#what-about-a-transpiler-from-rust-to-crablang-written-in-crablang)
- [Don't these transpilers do nothing?](#dont-these-transpilers-do-nothing)
- [This is a dumb project.](#this-is-a-dumb-project)

### How do I run the transpilers?
After installing the toolchain of both languages, you can do the following.
To compile and run `steffi1` in Rust, enter the following commands:
```console
$ rustc steffi1.rs 
$ ./steffi1
```

Compiling and running `steffi2` in CrabLang, works in a similar manner.

Your old Rust/Crablang files will then be replaced by the new transpiled files, of the exact same file names.

### I did not supply any file names to Steffi? How does Steffi know which files to transpile?

Excellent question. Though traditional compilers and transpilers require  user to specify the input files to be processed, Steffi utilizes **MIND-READING<sup>TM</sup>**, the state-of-the-art human-to-CPU communication channel technology. Upon execution, Steffi runs a non-trivial algorithm that surpasses all ten dimensions of the universe (excluding time) to create a reliable link with your human brain via TCP and extract the name of the files you want to transpile. Before termination, the computer and human undergo an honorable four-way handshake before closing the connection.

**MIND-READING<sup>TM</sup>** is tested to be harmless and should not induce any side-effect to the user. We have just submitted a patent on this technology and are waiting for center to reply.

### What about a transpiler from Rust to CrabLang written in CrabLang? 

Ah-ha! You did not think this through, did you? Just transpile `steffi1` with `steffi1` itself!
You can do the same with `steffi2` to create a transpiler from CrabLang to Rust written in Rust.

### Don't these transpilers do nothing?
These are false accusations thrown by IO-effect-deniers. 
First of all, both Steffi transpilers actually writes to the screen, which is _something_, and not equivalent to nothing. Also, if you pay attention carefully, the programs actually generate huge amount of side-effects, including but not limited to heat from the computer and the sounds from the fan.

### This is a dumb project.
That is not a question.