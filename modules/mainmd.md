# Modules

To make a module, simply fork this repo and add a new entry under the Modules section. However, keep this in mind:

 - Every module *must have it's own subfolder in the modules folder.* This will make the project much more manageable by reducing clashes.
 - Every module *should follow some guidelines.* Ideally, the content should be divided in the following files:
   - 00 Changes.md: Any changes made to the original system. This should, obviously, be the first thing a new player/QM reads. If the module also depends from other module (Adding content to it, for example) it should also be informed here.
   - 01 Creatures.md: All creatures added. Precalculations such as a creature's speed and HP should be done here.
   - 02 Magic: All the spells added. New spell categories should also be added here.
   - 99 Changelog.md: The changelog of the game, filled as the creator sees fit. It's advisable, however,to have properly maintained one.
 - Of course there can be deviation-- If you are adding many creatures it'd be wise to divide them by class along multiple Articles, but it's still for the convenience of players that the content is divided neatly.
