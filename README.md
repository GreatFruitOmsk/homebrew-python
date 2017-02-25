# homebrew-python
Install any version of Python under Homebrew.

1. Tap the repo via `brew tap GreatFruitOmsk/python`
2. Install python you need, e.g. `brew install python@3.5.3`

Since you cannot have multiple major versions installed simultaneously (e.g. 3.5 and 3.6) `brew` will fail to link them.  
But that's fine as you can either create virtualenv or modify `PATH` whenever needed.
