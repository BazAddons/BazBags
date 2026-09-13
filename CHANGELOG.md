# BazBags Changelog

## 077 — Fixed the stutter when picking up currency

**No more hitch when you gain currency.** Flying through Voidlight Marl
orbs (or picking up any currency) froze the game for about a second,
even with the bag closed. BazBags raised Blizzard's "Show on Backpack"
limit in a way that made Blizzard's own currency code do a thousand
times more work on every currency update. The limit is still lifted, but
the extra work is gone.

**Plays nicer with other bag addons.** Slots are now fully hidden when
the panel is closed, so addons that decorate bag slots (item level
overlays, for example) no longer scan BazBags' slots after every loot.

**Blizzard's currency window loads on its own schedule again.** BazBags
no longer forces it to load at login.
