# GildedRose-Refactoring-Kata
A few notes:
===========

- I would have refactored very differently if it was possible to modify the Item class, probably making it abstract with an "update" method and then subclassing it instead of putting the logic into separate item updaters
- I don't normally commit such small changes separately, but since this is a refactoring kata I wanted to make the steps I followed as clear as possible
- The UpdaterFactory choice based on lists of every different kind of items is probably overkill and not really a requirement.
- This refactoring is nowhere near complete: there's a lot of work left to do in the single updater classes but I think I've conveyed the general idea at this point
- The requirements and starting code are from [https://github.com/emilybache/GildedRose-Refactoring-Kata](https://github.com/emilybache/GildedRose-Refactoring-Kata), I just isolated the java code and turned it into a maven project for easier dependency management. Check out the link if you want to give it a try as well!

