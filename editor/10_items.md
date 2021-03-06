#Forge of the gods: how to craft super sweet user-made items!

##An equally awesome intro

All right, so you've got a totally supersweet bonus battle finished, but you can't help the feeling that something's missing… How about A TOTALLY FREAKING RAD UNIQUE ITEM WITH SPECIAL ABILITIES?!

##Launching the thingy

Okay, first things first, you need to fire up that level editor again!

(The last project you were working on will load automatically.)

See that "New Item" button at the bottom of the main menu? CLICK THAT SUCKER!

The game will ask you for an item ID – like with battles, the item ID is just the internal codename the game uses to keep track of the item. Players aren't ever going to see it, so it doesn't need to be anything human readable. I'm making my ID "guardherald", but you're free to make your item ID whatever the heck you want – this is your party!

Click accept, and BAM! You're in the item editor!

##Choosing your item:

So there's a bunch of buttons here, but don't worry, we're going to break it down for you piece by piece!

The first thing I'm going to do is decide what kind of item I want to make – I'm envisioning the Guard Herald's Harness, a super bad ass piece of heavy armor! So, the first thing I do is click the "Item Class" button – by default, it starts out as "weapon." Clicking on the button brings up all of the different classes of items I can make: Weapon, Armor, and Accessory. I select "Armor."

The next button is "Item Type." This button sets what specific type your item is WITHIN the Item Class that you've selected. Since the item class I've picked is Armor, the item types available to me are Heavy and Light. I select Heavy.

CONGRATULATIONS! You have heavy armor!

Of course, it only does 1 defense…

##Upping them numbers!

Okay, so how do we make this armor AWESOME?

To the right, you'll see a text field – this is the bonus this item gives the defender it's equipped to. You'll notice that underneath this text field is the word "defense_abs". This lets you know that the bonus you enter applies to the defense_abs stat. (Which stat is affected changes depending on the kind of item you're making – if we were making a sword, the stat would be attack.)

I want the Guard Herald to be pretty awesome, even in new game plus, so I'm going to make its bonus 50.

Pro tip: It's always a good idea to measure the item you're making against the items already in the game to make sure it isn't underpowered or overpowered. I looked at this list of all of the heavy armor items in the game while making the Guard Herald (available for your viewing pleasure on our official wiki page):

http://defendersquest.wikia.com/wiki/Heavy_Armor

Next we have the "Name" and "Description" buttons – these work just like the name and blurb buttons when you made your battle. Click on the button, click on the flag representing your language, and paste in whatever text you want people to see!

Now just click save and BAM! You've got yourself a bona fide piece of unique heavy armor!

##Loading some art

As awesome as this item is, I can't shake the feeling that it should be even MORE awesome…

Of course! It's that boring old default graphic!

Well, this is a problem easily rectified! Using your skills-of-an-artist, let's whip up some sprites that let the world know just how unique and bad ass this item is!

Each item in Defender's Quest has 2 sprites: a big one, for when the player is examining the item itself, and a small one, to be displayed at various places in the user interface where the big one won't fit (such as next to the defender it's equipped to in the party menu).

##THIS IS IMPORTANT:

The big sprite for your item HAS TO BE 64 x 64 pixels.

The small sprite for your item HAS TO BE 32 x 32 pixels.

Both of them need to be .PNG files or bitmaps (.bmp).

These are not polite suggestions, these are ABSOLUTELY MANDATORY!

Using a simple paint program and my incredible artistic talent (by which I mean copying, pasting, and recoloring the game's default art), I whip up these sexy graphics for the Guard Herald:


Ooh, soooo shiny!

Now, to attach them to my item! Simply click the "Change" button underneath an icon, find the folder you saved your custom art and, and load those puppies!

BAM! Now your item has gorgeous unique art!

##Special abilities:

Now, we could call it a day there – we've got a new item with nice stats and fancy new art! What more could you want from a unique piece of heavy armor?

How about UNIQUE SPECIAL PROPERTIES?!

That's right, you can give your items up to 2 strange and powerful special properties!

See that button down there in the special panel? The one that currently says "nothing" because there's nothing special about our item? TIME TO CHANGE THAT!

Click that sucker!

This brings up a list of the different kinds of special you can add your items. There's a ton of different things here, but for the purposes of this tutorial I'm only going to focus on a few. Since the Guard Herald is a bad ass suit of armor, I'm going to select "Strong." This makes it so that your item is strong against the kind of damage or enemy you specify. (It's worth noting that defensive specials are not limited to just armor – there's nothing stopping you from applying these specials to say, a sword! It's your item, go nuts!)

You'll notice that two new buttons pop-up next to the "Special" button – "PSI tax" and "If difficulty is…"

The PSI tax gives a penalty to Azra's PSI when this item is equipped. It's a good way of balancing superpowerful items (particularly Azra's books). I don't think the Guard Herald needs a handicap, so I leave the PSI tax at zero.

The "if difficulty is" button is another interesting way of balancing items – you can make it so that specials only kick in at certain difficulties. So for instance, an item can get even more awesome when playing on extreme! For the moment, I'm going to leave this set on "any."

Okay, on to the good stuff! The "vs. attack flavor" button lets you decide what exactly your item is going to be strong against. Go ahead and click on it!

As you can see, you can select from different types of damage OR from different types of enemy. For example, you could be strong against RANGED damage OR you could be strong against SHEEP type enemies. Is there a specific type of enemy you hate? This is the place to stick it to them!

I'm going to select "melee."

The next thing I can select is "damage interaction." This lets me decide how exactly my item is going to react to the kind of damage it's strong against. Go ahead and click it. As you can see, we've got a couple of options: we can apply a damage multiplier, dodge, or save.

The damage multiplier lets us decrease (or if we want to create a downside to the item, increase) the incoming damage that the item is strong against.

Dodge gives a percent chance to completely avoid the incoming damage that the item is strong against. (If you set the chance to 100%, the defender equipping this item will ALWAYS dodge incoming attacks of the flavor that they are strong against, making them de facto INVINCIBLE against that type of damage.)

"Save" is a little bit tricky. If your health is above a certain percentage, AND you take damage of the type you're strong against THAT WOULD ORDINARILY KILL YOU, you get "saved" instead – your health is reduced to 1, but hey, you're still alive!

I'm going to go with a straightforward damage multiplier for the Guard Herald. Incoming melee damage is multiplied by .5 (a.k.a. cut in half). It's worth noting that you can make this damage multiplier greater than 1 to take MORE damage from a specific attack type or enemy type, so you can use the Strong special to actually create weaknesses!

Click save and BAM! Here's the Guard Herald! It gives a 50 bonus to defense_abs AND reduces all incoming melee damage by half! Now that's pretty darn nifty!

##But that's not all!

To make the Guard Herald even niftier, I'm going to add a second special!

Clicking on the second Special button, I select "Stat". This makes it so that the item modifies a specific stat for the defender that has it equipped.

I set regen_abs to be multiplied by 1.5 – now the defender that equips the Guard Herald gets a 50% bonus to their regeneration!

Conversely, if I wanted to create a downside to the item, I could set the regeneration multiplier to .5 – now, the defender who equips this item gets their regeneration speed cut in half. (Making the first special a really great bonus and then counterbalancing it by making the second special a weakness is a great way to give players interesting choice when it comes to items.)

Other stats you can modify are attack, range, attack speed, defense, dodge, hp, and PSI! Plus, you can change the modifier to multiply, add, or subtract, so there's all kinds of effects you can create!

You could have a long sword that gives melee characters increased range, a suit of blood knight armor that doubles attack speed but cuts health in half, or a tunic that boosts dodge but lowers defense! And that's just using the Stat multiplier special – adding in what you learned about the Strong special will let you do even crazier things!

##Put it in that battle, yo!

Okay, so we have a totally awesome new item now! Time to put it in our battle!

Simply save your item, return to the main menu, and load that battle you made earlier.

Click the rewards buttons, and change the reward type to "Item." Now clicking the "reward value" button will give you a list of all of the items that you've made. Go ahead and slap that puppy on in there!

Hit the save button and CONGRATULATIONS! We now have a kick ass bonus battle with an even more kick ass item waiting as a reward at the end!

##Keep coming back for more!

This is just the tip of the user-made iceberg! There's all kinds of crazy things you can do with the item editor!

Over the coming weeks, I will be uploading new tutorials showing you how to make different kinds of items and levels! Tune back into learn how to make the Plague Doctor's Staff, the Gambler's Blade, Dragon Armor, the Slow Death Warbow, and much much more!
