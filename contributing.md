# Contributing

To make a module, simply fork this repo and add a new entry under the Modules section. However, keep this in mind:

 - Every module *must have it's own subfolder in the modules folder.* This will make the project much more manageable by reducing clashes. **Modules that do not follow this rule won't be added to the main repo at all.**
 - Every module *should* follow some guidelines. Ideally, the content should be divided in the following files:
   - **00 Changes.md**: Any changes made to the original system. This should, obviously, be the first thing a new player/QM reads. If the module also depends from other module (Adding content to it, for example) it should also be informed here.
   - **01 Creatures.md**: All creatures added. Precalculations such as a creature's speed and HP should be done here.
   - **02 Magic**: All the spells added. New spell categories should also be added here, ideally in their own subcategory.
   - **03 Equipement**: All items added, ideally categorized in articles if the content exceeds a few items.
   - **04 Vehicles.md**
   - **99 Changelog.md**: The changelog of the game, filled as the creator sees fit. It's advisable to have properly maintained one.
 - Of course there can be deviation-- If you are adding many creatures it'd be wise to divide them by class along multiple Articles, but it's still for the convenience of players that the content is divided neatly.
