# ProjectSquidFireMage

- Dumped project squid fire mage (not by me) (and the other unfinished rotations like rogue), ported to minibot and turned into a working addon (now defunc) by me. 
- Fully deobfuscated including original comments in code.


- Ran by known scammers Xen (not real Xen either) and Larry.
- Exit scammed after EWT shutdown by pretending to have EWT source code .

- Full of hilariously bad code, especially anywhere you see "I'm a genius" in one of the comments.

- This is all put into one file (zzz.lua), I have not broken apart the addon because it would take too much time.

Things you'll find hilarious

- Calls himself a genius for creating a caching layer on top of already cached functions
- Self-boasting April fools joke in which he saves the user from a fake GM
- Heavy copy pasting from Larry's scam rotations
- Magic numbers and logic for basically everything
- Massive rotation runner (why isn't this split into various components, who knows)
- Pointless reiteration of things like unitauras for the 50 million different checks he does (this is where you should have actually used proper caching)
- Perhaps the worst authentication ever made
- Laughable AOE circle prediction (often will place the edge of the AOE barely on the target instead of centering or predicting properly)

Things that are actually good

- Decent 1:1ness with SimC (you'll see he commented the SimC logic and implemented it below it)
- Excellent fire mage logic (has some major flaws in prediction, as well as performance, lots of magic numbers with 0 explanation provided)
- Pretty okay arena helpers (in terms of function offered to user, alerts, drawings, etc)
- Good GUI and nice custom textures (some 'stolen' media and code but doesn't really matter)
