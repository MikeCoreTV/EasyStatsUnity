# EasyStats
A set of C# Scripts for Unity to make creating stats, items, buying selling, and what happens from them all available in the inspector and without code.

You get 7 Components

One is the Stat Component - Ideal for making Currency, Health, Energy, Stamina, Mana, Etc.
(When calling functions in unity events you will be prompted with a string where you might expect a value input. this is so u can enter different stats. so instead of putting "10" you'd put "health.10")
(additionally, the remove stat function is just the name and the add stat function is the name,min,max,current so exp. "health.0.100.75" you'd create a stat named health with a minimum of zero a maximum of zero that is currently at 75)

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

(exp. <Item.Food.Name/> will show up as Food)

Stat Item and Stat Display - Does Both On the Same Text Element!

Almost everything is case insensitive so you should be able to not worry about how you're writing. (but still try to be cautious)
 
Works great with Unity.Event-based assets
Dialogue Speaker - https://assetstore.unity.com/packages/tools/audio/dialogue-speaker-178799
