jekyll-win32-standalone
=======================

Win32 standalone version of Jekyll

This is a NuGet package bundling Jekyll to allow for its use inside .NET projects (primarily for documentation).
This produces an environment able to mimic GitHub Pages or similar hosting environments, plus provides the flexibility to extend it.

## Inspiration

Inspired by Pretzel, Scribble - see additional projects as well

## Usage

* TODO *

## Contents

### Runtimes

 - Ruby environment
 - Python environment (2.7.5.1), based on Portable Python project

### Packages (gems) includes:

 - Jekyll 1.0.3
 - Liquid 2.5.0
 - Redcarpet 2.2.2
 - Maruku 0.6.1
 - Pygments 0.5.0

Note that each of these may contain their own licenses, which are contained within the relevant gems.


## Creation steps

More will be included in repro over time, steps currently involve:

 - Installing ruby environment, ensuring desired gems are downloaded
 - Run ocra to bundle up dependencies and create package
 - Extract package (as performance is significantly better once extracted rather than on a per run basis)
 

 

