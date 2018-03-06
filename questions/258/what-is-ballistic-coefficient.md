## What is 'Ballistic Coefficient'?

- posted by: [Tango](https://stackexchange.com/users/-1/65-tango) on 2011-11-03
- tagged: `ammunition`, `accuracy`, `terminology`, `ballistics`, `twist`
- score: 1

In regards to accuracy, I've seen a lot of forums reference the Ballistic Coefficient of a specific bullet.  What is this and is it something that can be calculated on the fly if I'm at the range?  Is it affected by anything in the rifle itself, such as 1/7 twist or 1/12 twist or is it solely based on the bullet itself?  Is it affected by the amount or type of powder in the round?


## Answer 263

- posted by: [Chris Upchurch](https://stackexchange.com/users/-1/79-chris-upchurch) on 2011-11-03
- score: 3

<p>One thing to keep in mind is that a ballistic coefficent is based on a standard reference projectile.  The default is the G1 projectile, which looks like a WWI artillery shell.  The closer a bullet's shape is to the reference projectile, the more accurate the ballistic coefficent will be.  Unfortunately, most of us aren't shooting rounds shaped like WWI artillery shells.  This means that G1 ballistic coefficents are only accurate for a single velocity.  As you get further from the reference velocity they become increasingly inaccurate.  </p>

<p>There is a different reference projectile, the G7, which is shaped much more like a long range boat-tail rifle bullet.  G7 ballistic coefficents are accurate over a much wider range of velocities than the G1 BC.  Most bullet and ammunition manufacturers don't provide G7 BCs for their bullets, but you can find them from other sources.  Not all ballistics calculators handle G7 BCs, but the better ones generally do.  I would recommend <a href="http://appliedballisticsllc.com/index_files/Book.htm" rel="nofollow"><em>Applied Ballistics for Long Range Shooting</em> by Bryan Litz</a> for a much more detailed explanation of ballistic coefficent and G7 BCs for many popular long range bullets.</p>



## Answer 262

- posted by: [OldWolf](https://stackexchange.com/users/-1/111-oldwolf) on 2011-11-03
- score: 2

Ballistic coefficient is a function of the drag coefficient, mass and diameter of the bullet. It's based on the bullet itself, not the powder or the rifling. There are a number of pre-prepped tables for existing bullets. The general calculation is:

[From wikipedia:](http://en.wikipedia.org/wiki/Ballistic_coefficient)

BC = M/(Cd * A) = (rho * l)/Cd

M = Mass

Cd = Coeefficient of drag

A = cross sectional area

rho = average density

l = body length

**For bullets it's**

BC = SD/i = M/(i*d2)

Edit:

SD = sectional density,mass of bullet in pounds or kilograms divided by its caliber squared in inches or meters; units are lb/in2 or kg/m2.
i = form factor, Cb/Cg (Cg ~ 0.5191)

Cb = Drag coefficient of the bullet

Cg = Drag coefficient of the G1 model bullet

M = Mass of object, lb or kg

d = diameter of the object, in or m



## Answer 271

- posted by: [Bryson](https://stackexchange.com/users/-1/32-bryson) on 2011-11-03
- score: 2

<strong>Ballistic coefficient (BC) is the measure of a bullet's ability to overcome air resistance in flight.</strong>

It is not something you would need to calculate on the fly at the range, but if you had all the info you could. A caveat: if you already had all the info you would need to calculate this, it would seem that you're in the process of manufacturing and selling bullets. Getting all that info is much more difficult than just reading the BC printed on the box of bullets or reading it online if you're buying whole cartridges.

<strong>Note that the BC only refers to the bullet, which is a single piece of the cartridge or round. Nomenclature is key here, as in this context "bullet" does not mean the casing, primer, powder charge, and bullet combined, or the many possible combinations of same. <em>Only</em> the bullet.</strong>

The detailed equation for calculating the ballistic coefficient of bullets is below, with an explanation of the variables available on <a href="http://en.wikipedia.org/wiki/Ballistic_coefficient#Bullet_performance">Wikipedia</a>:

<img src="http://upload.wikimedia.org/wikipedia/en/math/c/4/9/c494b0416825cdc5fa71474121f6dfa0.png" alt="Ballistic Coefficient Formula" />

The BC is not affected by the twist rate of a barrel, which affects the stability of the round in flight. Although an unstable bullet's BC will be terrible, as long as the bullet is stable the BC will stay the same. If 62gr ammo from an AR-15 is stabilized by a 1:9 twist, its BC will be the same as if it were stabilized by a 1:7 or 1:8 twist, only changing when stability is lost.



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
