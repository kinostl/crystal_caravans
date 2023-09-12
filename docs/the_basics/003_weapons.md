# Weapons

Every tribe has a signature weapon. Clavats have swords. Lilties have lances. Yukes have magic hammers. Selkies have bludgeons.

These signature weapons provide extra dice when you roll Combat, and some even increase your Combat stat while fighting.

Some Accessories allow you to use weapons from outside your tribe.

-   _Clavats_ start with a **Copper Sword**.
-   _Lilties_ start with an **Iron Lance**.
-   _Yukes_ start with an **Orc Hammer**.
-   _Selkies_ start with an **Aura Racket**.

{{ read_excel('../data.xlsx', engine='openpyxl', sheet_name="starting_weapons") }}

## Focus Attacks

Weapons have "Focus Attacks". When you roll a crit you activate your Focus Attack. Focus attacks can damage multiple targets, cause status effects, and all kinds of effects.

A Focus Attack's Status Effect lasts a number of turns equal to the number of crits that activated it.

### Clavat

-   **Power Slash** For every crit, deal a point of damage to the target.
-   **Piercing Sweep** For every crit, deal a point of damage to another target.
-   **Bash**
-   **Shadowblade**
-   **Soulshot**

### Lilties

-   **Cyclone Slash** For every crit, another target is also attacked.
-   **Psi Blast** For every crit, a target can not use magic.
-   **Bladestorm**
-   **Cross Slash**
-   **Pulse Thrust**
-   **Avalanche**

### Yuke

-   **Power Bomb** For every crit, burn a target.
-   **Wave Bomb** For every crit, freeze a target.
-   **Shock Bomb** For every crit, paralyze a target.
-   **Magic Bomb** For every crit burn another target. Repeat this for freeze and paralyze.

### Selkie

-   **Aura Blast** For every crit, deal a point of damage to a target.
-   **Stampede** For every crit, stop the target.
-   **Dual Blast** For every crit, attack the target again. Ignore crits on those attacks.
-   **Power Kick** For every crit, stop the target and deal a point of damage to it.
-   **Meteor Strike** For every crit, attack the target again.
    -   _(Crits on these attacks activate Meteor Strike again)_
