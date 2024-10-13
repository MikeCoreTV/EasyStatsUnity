# EasyStats
A set of C# Scripts for Unity to make creating stats, items, buying selling, and what happens from them all available in the inspector and without code.

You get 7 Components

One is the Stat Component - Ideal for making Currency, Health, Energy, Stamina, Mana, Etc.

One is Stat Item - Ideal for managing things like Food, collectibles, Keys, Potions, Etc.

(Stat and Item are Similar in many ways and can be used interchangeably, Just use whatever suits you best for your needs)

Two Being Buy/Sell

Stat Buy - is ideal for, well, buying things, buy takes away from stats and gives to items

Stat Sell - is ideal for, well, selling things! Sell gives to stats and takes from items

The last three components are UI components

Stat Display - Updates a Text Element from a specified stat component with the following... (literally just type these into your text element along with the rest of your text)

<Name.Name/>
<Name.Maximum/> 
<Name.Minimum/>
<Name.Current/>

(exp. <health.Name/> will show up as health) Or (<health.Current/> Will show up as healths current value (and automatically updates with changes)

Stat Item Display - Updates a Text Element from a game objects numerous item stat components with the following... (literally just type these into your text element along with the rest of your text)

<Item.Name.Name/>
<Item.Name.Owned/> 
<Item.Name.Max/>

Stat Item and Stat Display - Does Both On the Same Text Element!

Good assets to use with EasyStats:
Feel - https://assetstore.unity.com/packages/tools/particles-effects/feel-183370

Trigger Manager - https://assetstore.unity.com/packages/tools/physics/trigger-manager-267104

Press E - https://assetstore.unity.com/packages/tools/game-toolkits/presse-interaction-system-for-unity-291733

Dotween Pro - https://assetstore.unity.com/packages/tools/visual-scripting/dotween-pro-32416

Easy Save - https://assetstore.unity.com/packages/tools/utilities/easy-save-the-complete-save-game-data-serializer-system-768

Rewired - https://assetstore.unity.com/packages/tools/utilities/rewired-21676

Dialogue Speaker - https://assetstore.unity.com/packages/tools/audio/dialogue-speaker-178799
