# 100 - What is publishing?

A process of exporting particular data from your work scene to be shared with others.

Think of publishing as a checkpoint between two people, making sure that we catch mistakes as soon as possible and don’t let them pass through pipeline step that would eventually need to be repeated if these mistakes are not caught.

Every time you want to share a piece of work with others (be it camera, model, textures, animation or whatever), you need to publish this data. The main reason is to save time down the line and make it very clear what can and cannot be used in production. This process should mostly be handled by publishing scripts but in certain cases might have to be done manually.

Published assets should comply to these rules:

- Clearly named, based on internal naming conventions.
- Versioned (with master version created for certain types of assets).
- Immediately usable, without any dependencies to unpublished assets or work files.
- Immutable

All of these go into the publish folder for the given entity (shot, asset, sequence)

**NOTE**: Keep in mind that while publishing the data might take you some extra time, it will save much more time in the long run when your colleagues don’t need to dig through your work files trying to understand them and find that model you saved by hand.
