## What is the effect of additional or fewer lands and grooves in a Rifled Barrel

- posted by: [Community](https://stackexchange.com/users/-1/-1-community) on 2011-11-03
- tagged: `gunsmithing`, `barrel`, `lands`, `grooves`
- score: 1

Do more lands and grooves always improve the bullet stability in flight? Is there a minimum number for a specific caliber?


## Answer 233

- posted by: [Mason](https://stackexchange.com/users/-1/19-mason) on 2011-11-03
- score: 1

<p>The number of lands and grooves is not relevant for most people. What is important is the twist rate of the rifling, generally specified in number of inches for a full rotation. You can calculate a stability factor for a bullet given the bullet weight, caliber, length, muzzle velocity, and barrel twist rate, plus the temperature and pressure of the air where you are firing. All else being equal, longer bullets, lower twist rates, and lower atmospheric temperatures and altitudes make bullets less stable. Generally, once the stability is above the limit, the bullet will fly straight, and there is no benefit to adding more stability. If the stability is below the limit, then the bullet will tumble in flight and generally be wildly inaccurate.</p>

<p>For common calibers firing factory loads, this is generally not an issue, as they are all pre-calculated to be stable in all ordinary conditions. The only somewhat common case I know of where this is a problem is for firing M855 or 62 grain bullets in AR15s with the early-model 1 in 12 inch twist barrels. Doing this will reportedly result in group sizes of 1-2 <strong>feet</strong> at 100 yards. If you are doing custom work with unusual ammunition types or calibers, then you should calculate your own stability factors to verify stability.</p>

<p>Some links for more information:</p>

<p><a href="http://www.jbmballistics.com/cgi-bin/jbmstab-5.1.cgi" rel="nofollow">Stability Calculator</a></p>

<p><a href="http://ammo.ar15.com/ammo/project/perf_twists.html" rel="nofollow">AR15.com ammo FAQ with more detailed description</a></p>



## Answer 237

- posted by: [Bryson](https://stackexchange.com/users/-1/32-bryson) on 2011-11-03
- score: 1

<strong>Simply put, bullet stability is determined by the rifling's twist rate, and not by the number of lands and grooves imparting the twist. Twist rate is dependent upon the length of the bullet and not the weight, it just happens to be that bullets of heavier weights in a given caliber can only grow in length as they increase in weight.</strong> When selecting a barrel many barrel makers will allow you to select your preferred number of lands and grooves. Sometimes for more money, sometimes as part of the regular price. At almost all levels of shooting this is not something that needs to be worried about, and more focus should be paid to the twist rate. To know your desired twist rate, you will need to know the range of bullet weights you will be shooting. It is possible to both under- and over-stabilize a bullet.

#Bullet stability and twist rate
Twist rate, as expressed in most modern weapons, is the length of barrel required to complete one full rotation of the bullet as it travels through. A 1:7 ("one-in-seven") twist is one full rotation for every 7 inches of barrel length. To calculate the amount of twist needed to stabilize a bullet you would use a formula known as the <a href="http://en.wikipedia.org/wiki/Rifling#Twist_rate_and_bullet_stability">Greenhill Formula</a>:

<img src="http://upload.wikimedia.org/wikipedia/en/math/8/4/d/84d1d28d700535884f8a2c2c2403b641.png" alt="The Greenhill Formula" />

 - C = 150 (use 180 for muzzle velocities higher than 2,800 f/s)
 - D = bullet's diameter in inches
 - L = bullet's length in inches
 - SG = bullet's specific gravity (10.9 for lead-core bullets, which cancels out the second half of the equation)

Note that the length of the bullet is used, and not its weight. <strong>The longer the bullet becomes, the more spin it requires to stabilize. In a given caliber, a bullet can only expand in length as its weight increases, but weight is not the deciding factor.</strong> 

Early AR-15 rifles, before being adopted officially by the military, had a 1:14 twist rate suitable for firing only very light bullets. As bullet weights (and lengths) increased this has reduced to the current rate of 1:7. Commercial rifles come in, commonly, 1:7, 1:8, and 1:9. When firing, for example, 55gr or 62gr bullets any of these rates will do. However, if you were to fire a 40gr varmint round through a 1:7 you would rip the copper jacketing off. Conversely, if you fired a 77gr bullet through a 1:9 you would lack the stabilization that bullet requires, and your groups would be large and erratic. At relatively close ranges you would experience bullet tumbling and other erratic behavior.

#Bullet stability and the number of lands/grooves
The number of lands and grooves in a barrel is not impoartant, but the surface area ratio between the land width and groove width is. This ratio is what determines things like drag, blowby, and tendancy to foul. The fewer grooves you have, the easier it can be to clean fouling from the barrel. A smaller number of lands and grooves can also affect a barrel's lifespan. <a href="http://www.riflebarrels.com/faq_lilja_rifle_barrels.htm#3%20Groove%20and%206%20Groove">From barrel maker Lilja</a>:

> A few years ago we started to make barrels in a 3 groove configuration
> too at the request of some varmint hunters who were looking for longer
> barrel life. They were chambering barrels for hot 22 caliber varmint
> rounds and shooting the throats out of conventional 6 groove barrels
> fairly fast. We reasoned that if we reduced the number of grooves to 3
> but kept the ratio of land to groove width the same (ie. the lands are
> twice as wide in a 3 groove barrel as compared to a 6 groove) that
> there would be more land area to resist heat erosion.
> 
> Well, it turned out that barrel life did increase and that accuracy
> stayed at least the equal of comparable 6 groove barrels. It is hard
> to put a percentage increase on barrel life but a conservative
> estimate might be 20%.
>
>...
>
>And we found that as a side benefit the 3 groove barrels seemed to foul
>very little and clean up quickly. We attributed this to the reduced
>number of corners inside collecting powder and copper fouling.

Additionally, other barrel makers have stated that, as long as the ratio of lands to grooves is relatively constant, there is no appreciable difference in accuracy among 3-,4-,5-,6- and 8-groove barrels.

Barrel maker Krieger has said:

> There isn't any advantage to the shooter. ... Barrel makers use
> different numbers of grooves for ease of manufacturing and ...
> marketing hype.

Higher groove count barrels have slightly slower bullet velocities and also may foul a bit more quickly due to the higher number of edges cutting the bullet jacket and trapping residue.  Conversely, lower groove count barrels have slightly higher velocities, and foul less easily.

In addition to marketing another consideration a barrel maker uses is the difficulty of manufacture. Some say that even numbers are much easier, and some say that odd numbers are easier. Button rifling, hammer forging, on and on. <strong>Lands-and-grooves is one of those voodoo magic kinds of things that you're very unlikely to ever worry about.</strong>

In addition to all of this, there are other methods of imparting twist to a bullet. The most widely used is "polygonal rifling," in which there are no traditional lands and grooves, but rather flat sides inside the barrel that twist along its length. The merits of this system can be left for another question as they're outside the scope of this one, but the differences here are again more related to velocity, fouling, etc. and not the stability of the bullet in flight.



---

All content is licensed under [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/).
