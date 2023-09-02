# River Belle Path

> They say that wicked creatures prowl the road along this beautiful riverbank, but nobody has ever seen one.
>
> I once asked a man why.
>
> He simply replied, "Because anybody who happens upon one is promptly eaten!"
>
> But it is long since anyone has met such a fate.
>
> For nowadays, people take another route,
> far away from the spooky old road.
>
> Only we walk the old way now...
>
> travelers in crystal caravans.

**Goal** Defeat the _Giant Crab_ protecting the Myrrh Tree. (Don't worry, the Myrrh Tree can make more.)

```mermaid
graph LR
    S>Start]---GG[Goblin Gate];
    GG---GC((Goblin Courtyard));
    GC---GL{Goblin Labyrinth};
    GC---SC[/Scenic Cliff\];
    GL-->BR(((Giant Crab)));

    click S "#entrance"
    click GG "#goblin-gate"
    click GC "#goblin-courtyard"
    click GL "#goblin-labyrinth"
    click SC "#the-scenic-cliff"
    click BR "#defeat-the-giant-crab"
```

<div class="print-site-plugin-ignore" markdown>

!!! Tip "Node Maps on The Web"

    This map is interactive! Click on a node to jump to it.

</div>

## Monster List

Normally this would have multiple encounter lists for which year it is or which visit number this is. Since this is an introductory version of the book, we're going to assume its the first visit on the first year.

<section class="monster-list" markdown>

**Goblin** 3 Hearts  
Combat 2, Unity 1, Magic 0  
_Resistant to_ -  
_Vulnerable to_ Fire, Lightning  
Appears in groups of 3 to 4.

**Goblin Chieftan** 18 Hearts  
Combat 2, Unity 2, Magic 0  
_Resistant to_ -  
_Vulnerable to_ Fire  
Provides other Goblins an extra dice on all rolls.  
Unity: Other Goblins get +1 to their stats this turn.

**Mu** 10 Hearts  
Combat 2, Unity 1, Magic 2  
_Resistant to_ -  
_Vulnerable to_ Fire, Ice  
Able to cast Thunder.  
May drop Thunder Magicite upon defeat.

**Hedgehog Pie** 12 Hearts  
Combat 2, Unity 1, Magic 2  
_Resistant to_ -  
_Vulnerable to_ Ice, Lightning  
Able to cast Fire.  
May drop Fire Magicite upon defeat.

</section>

!!! Tip "May drop upon defeat."

    Ultimately this is up to your Game Master. A nice way of handling it might be someone rolling Luck after the fight.

    If you do this, only one person should probably roll. It makes it more exciting.

## Entrance

The Caravan finds itself unable to move itself any further. The players will have to continue on foot. The Goblins that live here have destroyed the ground and dried it out. Its craggly and difficult to even walk on. Maybe one day this trade route will heal.

The Entrance is always a plain Exploration Area.

**_Exits_**

-   Goblin Gate

## Goblin Gate

The Goblins have setup a defense here. A large gate made out of fallen trees. The Miasma has dried them out and made them hard as stone. A quick glance can tell that it has mechanisms behind it allow it to open when a stone tablet key is put into the pedestal nearby.

If this is a Combat area, spawn some goblins in and around the wall. Goblins can throw rocks and swing swords.

If this is a Puzzle area, the gate is locked and the key has been hidden somewhere inconvenient. Probably hanging off the top of the gate where only a polearm can reach it.

If this would be an Exploration area when the type is rolled, it becomes a Puzzle area instead.

**_Exits_**

-   Goblin Courtyard

## Goblin Courtyard

The ground here is softer, tamped by goblins walking on it every day. The only hint of green grows on the very edges where the ground meets cliffs. Another gate is here.

If this would be a Combat area, spawn some Goblins and a Chieftan.

If this would be a Puzzle area, the door is locked. Theres a treasure box.  
It requires a Fire Spell (or some creativity) to open. It has the key.

If this would be an Exploration area, theres a gravel beach next to the river.  
The players may change the element of their Chalice to Wind or Water while they're here.

**_Exits_**

-   Goblin Labyrinth
-   The Scenic Cliff

## The Scenic Cliff

Roll for The Goblin Labyrinth before describing this area.

A surprisingly long path through a beautiful piece of forest up a small hill. The Myrrh tree's roots must have reached this place. The pathway ends at a cliff overlooking the Goblin Labyrinth.

If this is a Combat, spawn a Mu and a Hedgehog Pie.  
They're trying to destroy the forest. Its not going well for them.

If this is a Puzzle, there are trip wires hooked up to bells in the area below.

If this is an Exploration, the air smells cleaner than normal. Players may spend an action to put a Myrrh Leaf in an Accessory slot. You may expend the Myrhh Leaf to clear a status effect.

**_Exits_**

-   Goblin Courtyard
-   Drop into the Goblin Labyrinth

## Goblin Labyrinth

This was once a large field where traders could take a break. Some say it was a bazaar at one point even. Now its a field of shallow trenches where grass struggles to grow.

If this is a Combat, some monsters are hiding in the trenches. Spawn a Mu, Hedgehog Pie, and 3 Goblins.

If this is a Puzzle, there are magic traps buried in the ground. They're unstable Fire Magicite that explode if they're stepped on. An Explosion is a Fire spell, but each hit counts as a crit.

If this is an Exploration, the miasma thickens. It is not a beautiful place, but you can see what it once was. You can make a Unity roll to fill yourself with hope and heal a heart.

**_Exits_**

-   Goblin Courtyard
-   Defeat the Giant Crab

## Defeat The Giant Crab

The Myrrh Tree sits in a secluded grotto with a massive waterfall underneath it. Thick foliage grows well here in colors that only those in Crystal Caravans get to see. The ground rumbles and the waterfall splits apart. A giant crab jumps out from a cave behind the waterfall, slams into the ground, and screeches. Its ready for combat.

<div class="boss-monster" markdown>

**Giant Crab**{.boss-name} 30 Hearts  
Combat 3, Unity 0, Magic 2  
_Resistant to_ Thunder, Slow, Stop  
_Vulnerable to_ -

When the Giant Crab receives a critical hit, or drops below 10 or 20 hearts, the players choose to remove the left or right claw.

When the Crab loses a claw it loses 1 point of Combat.

_Crab Hammer_ --- Combat: The Crab slams the ground, roll combat for each claw. Each roll attacks a new target.  
_Megavolt_ --- Magic: Use only without claws. The Crab attacks with a huge beam of electricity. Also paralyze a target for each crit.

**_Desperation Attacks_**

Giant Crab can only use these after dropping below 20 hearts.

_Crab Drangoon_ --- Combat: The Crab jumps around. Each Hit harms a different target.  
_Bubble Tea_ --- Magic: Sticky bubbles fill the air. All players roll Luck. Any who fail are Slowed.  
_Static Rush_ --- Use only with a claw. The Crab charges. Roll Combat and Magic to attack.

</div>
