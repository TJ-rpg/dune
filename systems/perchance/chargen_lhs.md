dsix = {1-6}
dfour = {1-4}
dtwenty = {1-20}

bondtxt
  [if (b=="Fieldwarden"||(b=="Outrider"&&addbnd==1)) {bnd=2,""} else {bnd=1,""}]<b>Bond: </b>[bond][if (bnd==2) {"<br><br>Your background grants you a second bond: " + [bond]} else {""}]

background
  1_Aurifex
    bgname = Aurifex
    blurb = You are an artisan of the arcane, a smith of subtle forces. In the crucible of your workshop, the laws that govern this world are warped to suit your needs.
    name
      Hestia
      Basil
      Rune
      Prism
      Ember
      Quintess
      Aludel
      Mordant
      Salaman
      Jazia
    event1 = <b>What went horribly wrong?</b><br> [b.event1tbl]
    event1tbl
      There was an explosion, and you lost your sense of smell. Well, almost: you can sniff out gold as a pig does truffles. Take a <b>Tin of Snuff</b> (6 uses) to dampen the impact. Use it every day or become <a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#deprivation--fatigue" target="_blank"><i>deprived</i></a>.
      You dematerialized a beloved pet. Now it follows you around, invisible but always present. Although it cannot interact with the physical realm, you are able to share its senses. (Add a <b>Fatigue</b> each time.) It follows basic commands.
      You were exposed to a long-acting truth serum whose effects have yet to wear off. The disorder has its advantages: you cannot repeat lies you’ve heard, either.
      You were adept at creating <i>fake</i> gold, which is almost as good. Eventually, your ruse was discovered, and you had to make a hasty retreat. Take a heavy <b>Metal Ingot</b> and <b>Gold Powder</b> (3 uses).
      Your alchemical recipe worked, but a rival stole the blueprint before your claims could be proven. Take a prototype <b>Blunderbuss</b> (d12, <i><a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#attack-modifiers" target="_blank">blast</a>, bulky</i>) that takes one round to reload, and a taste for revenge.
      Ridiculed for discovering how to turn gold into <i>lead</i>, you were a laughing stock. Take a bottle of <b>Universal Solvent</b> (2 uses) that dissolves anything it touches into its constituent parts.
    event2 = <b>What alchemical marvel is the product of your latest ingenuity?</b><br> [b.event2tbl]
    event2tbl
      <b>Pyrophoric Gel</b> - A sticky green fluid that catches fire when exposed to air. It lasts for 8 hours and cannot be extinguished.
      <b>Blast Sphere</b> - A head-sized iron ball filled with explosive powder that detonates on impact. d12, <i><a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#attack-modifiers" target="_blank">blast</a>, bulky</i>.
      <b>Aqua Vita</b> - Purifies any liquid, converting it to pure water. Drinking it cures 1d6 STR. 1 use.
      <b>Mimic Stone</b> - Records a short phrase that can later be played back.
      <b>Spark Dust</b> - Ignites easily and quickly. Useful for starting a fire or as an incendiary device. 3 uses.
      <b>Homunculus</b> - A miniature clay replica of yourself that follows your every command. It hates being enthralled to you and complains bitterly whenever possible. Any damage done to the homunculus is also done to you. 3 HP, 4 STR, 13 DEX, 5 WIL
    equip = Lantern<br>Oil Can (6 uses)<br>Needle-knife (d6)<br>Protective Gloves (petty)
  
  2_Barber-Surgeon 
    bgname = Barber-Surgeon 
    blurb = You walk the line between healer and harrower, knowing the frailty of the flesh but also the secrets that lie within. With the right tools, life and death are merely words.
    name = {Wilmot|Patch|Lancet|Sawbones|Theo|Cutwell|Humor|Landsford|Goodeye|Johanna}
    event1 = <b>How have you “improved” yourself?</b><br> [b.event1tbl]
    event1tbl
      You have a replacement <b>eye</b> that can magnify objects, act as a telescope, and provide minimal night vision. You cannot wear anything metal on your head, and the presence of strong magnets make you <a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#deprivation--fatigue" target="_blank"><i>deprived</i></a>.
      One <b>foot</b> is mostly metal (kick, d6), and you treat some Tough terrain as Easy. Carry a <b>Oil Can</b> (6 uses). Without a daily application, you are <a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#deprivation--fatigue" target="_blank"><i>deprived</i></a> and noisy.
      One of your fingers has been swapped, the bone replaced by gold and iron. Take a <b>Hook</b> and a <b>Screwdriver</b> that can attach to the fingertip.
      Both <b>ears</b> have been surgically enhanced, tripling your hearing. You can focus on a specific sound, such as a conversation, at a great distance. You wear an ear flap to protect against sudden loud noises (WIL save to avoid temporary paralysis).
      Your <b>chest</b> is lined with alchemical sigils, <i>toughening the skin</i> (1 <a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#armor" target="_blank">Armor</a>). Wearing other metallic armor nullifies the effect
      One <b>arm</b> is fully metal and comes off at the shoulder. It can be used as a weapon (d8, <i>bulky</i> when not attached) and can move independently if you are within sight of it.
    event2 = <b>What rare tool is essential to your work?</b><br> [b.event2tbl]
    event2tbl
      <b>Regrowth Salve</b> - Regrows a body part over the course of a day. 1 use.
      <b>Graftgrub</b> - A small worm that can fuse inanimate objects with parts of the body. 1 use.
      <b>Woundwax</b> - Heals wounds from fire or chemicals (restoring full STR) but nothing else. 2 uses.
      <b>Quicksilver</b> - A stimulant. Go first in combat, and automatically pass any WIL saves for one hour. <i>Addictive:</i> Save STR or become <a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#deprivation--fatigue" target="_blank"><i>deprived</i></a> after 24 hours without it. 4 uses
      <b>Pneuma Pump</b> - Portable iron lungs (<i>bulky</i>). Enables life-saving surgery or underwater breathing.
      <b>Lodestone</b> - Draws out dangerous elements from the body and acts as a powerful magnetic force.}
    equip = Torch (3 uses)<br>Bonesaw (d6)<br>Bandages (3 uses)<br>Leech (restores 1 STR, 3 uses)<br>Stained Medical Finery (petty)
  
  3_Beast Handler 
    bgname = Beast Handler 
    blurb = You alone can walk among the creatures of the wild, fearless and in control. You share a connection with animals that others can only dream of… so long as you don’t become their snack.
    name
      Amara
      Wulf
      Mireille
      Soren
      Freki
      Aster
      Gerrik
      Boreas
      Veda
    event1 = <b>What creature is your specialty?</b><br>{Arachnids - Take a <b>Quick-Flame Rod</b> and an <b>Oil Can</b> (6 uses). It can destroy a large spider nest in seconds.|<b>Felines</b> - Take a sack of <b>Whiskerwort</b>. Its odor can calm and control even the largest of cats.|<b>Canines</b> - Take a wreath of <b>Wolfsbane</b> and a <b>Large Net</b>. Effective against werewolves as well.|<b>Birds</b> - Take a <b>Warble-Whistle</b> (3 charges). It can imitate any bird call and can even be used to send simple messages. Recharge: Feed a baby bird as its mother would, then blow.|<b>Rodents</b> - Take a <b>Pan Flute</b> that emits a high-pitched sound that only rodents can hear. So long as you play, they will follow, even to their deaths.|<b>Serpents</b> - Take a <b>Warming Stone</b> that generates an irresistible heat and a vial of <b>Antitoxin</b> (2 uses).}
    event2 = <b>What have you learned from the creatures of the wild?</b><br>{That there is far more to the world than meets the eye. With quiet concentration, you can borrow the senses of a nearby creature of your <b>specialty</b>.|That the behavior of beasts is a language in itself. When observing beasts of your <b>specialty</b> you gain insight into weather patterns and impending disasters.|That the pulse of the hunt is a powerful impulse. You have a sense for when predators, even those <b>not of your specialty</b> are near.|That the land is a language unto itself. Your chance of becoming lost in a terrain dominated by the beasts of your <b>specialty</b> is reduced by one step (e.g. 4-in-6 becomes 3-in-6).|That nature’s symphony can be heard if you attune to its rhythm. When surrounded by creatures of your <b>specialty</b>, they can alert you to approaching danger before it arrives.|That survival is all about adaptability. Once per day, you may take on a simple feature from a creature of your <b>specialty</b> (webbed fingers, night vision, etc.). Add a <b>Fatigue</b> each time.}
    equip = Torch (3 uses)<br>Leather Whip (d6)<br>Soporific Darts (STR save or fall asleep, 6 uses)<br>Lure<br>Rope (25ft)
  
  4_Bonekeeper
    bgname = Bonekeeper
    blurb = You are a shepherd to the departed. You listen to the final whispers of the dead as they descend into the cold, unyielding earth. You know that to fully celebrate the gift of life, we must honor its finale as well.
    name = {Rook|Ebon|Moro|Yew|Pall|Leth|Bea|Barnaby|Vesper|Leder}
    event1 = <b>What did you take from the dead?</b><br>{A <b>crow-shaped amulet</b>. You can ask a question of the dead but must add a <b>Fatigue</b> each time. They do not always speak truthfully.|A <b>mortal wound</b> from a freed <i>revenant</i>. You were healed, but the disfigurement has made you a pariah. You require neither air nor sustenance but are still subject to pain and death. Trapped between worlds, the dead see you as one of their own.|A <b>Blood Pail</b> (bulky) from a local death-cult. Empty it to raise a servant built from whatever is buried below, with 6 HP, 1 <a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#armor" target="_blank">Armor</a>, 13 STR, 11 DEX, 4 WIL, and shard fists (d8+d8). Only one servant can be raised at a time. If destroyed, you permanently lose 1d4 STR. <b>Recharge:</b> Fill with the blood of a dying warrior.|A <b>burial wagon</b> (+6 slots, slow) from your last job. It came with a stubborn old <b>donkey</b> (+4 slots, only +2 slots if pulling wagon).|The <b>Detect Magic</b> <a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#spellbooks" target="_blank">Spellbook</a>, stolen from an ancient library. Your family worked in service to an obscure underworld deity, but you lost your faith. Though exiled, you continue to serve, even as an apostate. Detect Magic: You can see or hear nearby magical auras. <i>Becomes warm to the touch when magic is used nearby</i>.|A plague doctor’s mask, after its owner succumbed to the disease that wiped out everyone you once knew. They should have kept it on.}
    event2 = <b>What tool was invaluable in your work?</b><br>{<b>Manacles</b> - Though old, it’s still effective even against the very strong. You don’t have the key.|<b>Sponge</b> - Supposedly made from the remains of a rare sea creature. It never seems to dry out.|<b>Pulley</b> - Great for moving gravestones, rocks, or even bodies.|<b>Incense</b> - Perfect for rituals or to keep the flies at bay. Cools the blood.|<b>Crowbar</b> - d6 damage. Sometimes you just need to get the damn thing open!|<b>Repellent</b> - Powerful stuff. Its faded label makes it unclear what it is actually <i>meant</i> to repel, though. Perhaps everything. 3 uses.}
    equip = Lantern<br>Oil Can (6 uses)<br>Stake (d6)<br>Chains (10ft)
  
  5_Cutpurse
    bgname = Cutpurse
    blurb = You live in the grey space between those who have power and those who don’t. You find opportunity where others see only chaos. With nimble fingers, you unburden both the richest merchant and the lowliest guard.
    name = {Arlo|Lyra|Eamon|Salina|Elara|Freya|Bull|Sparrow|Ivy|Silas}
    event1 = <b>What was your last big job?</b><br>{A noble’s summer home. The place was full of fancy wine (+20gp) but not much else. Take <b>Fence Cutters</b>.|A bank. (You were caught.) You bear a brand only visible by firelight, and anyone who sees the mark can ask you for a beer. Take <b>Retractable Wires</b>.|A guild warehouse. Take a <b>Ladder</b> (<i>bulky</i>, 10ft) and <b>Blinding Powder</b> (1 use).|Moneylender. Someone beat you to the job but left behind a <a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#scrolls" target="_blank"><b>Scroll</b></a> of <i>Arcane Eye (petty)</i>. Arcane Eye: You can see through a magical floating eyeball that flies around at your command.|Constable’s quarters. You escaped but left some friends behind. Take <b>Strong Silk Rope</b> (30ft) and a queasy feeling.|A university. You were seen but not pursued. You still don’t know why. Take <b>Smoke Pellets</b> (3 uses).}
    event2 = <b>What helps you steal?</b><br>{<b>Catring</b> - 2 charges. Climb up walls and fall safely. <b>Recharge:</b> Place the ring on a stray cat’s tail.|<b>Gildfinger</b> - 1 charge. A finger glove that mimics any mundane key. <b>Recharge:</b> Bundle it with at least 100gp for a night.|<b>Glimpse Glass</b> - 3 uses. A monocle that lets you see through walls or other obstructions. It shatters after the last use.|<b>Sweetwhistle</b> - 1 charge. Listeners hear a soft, familiar voice in the distance that they cannot resist following. <b>Recharge:</b> Lose a dear memory. (Describe it.)|<b>Vagrant’s Veil</b> - 1 charge. Wear it to blend seamlessly into crowds, appearing as a simple pauper. <b>Recharge:</b> Donate the day’s winnings to the poor. <i>Petty</i>|<b>Reverse Teetotum</b> 	1 use. When spun, time skips backwards 30 seconds. Everyone remembers what happened.}
    equip = Torch (3 uses)<br>Twin Daggers (d6+d6, <i>bulky</i>)<br>Padded Leather (1 <a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#armor" target="_blank">Armor</a>)<br>Lockpicks<br>Black Outfit (<i>petty</i>)
  
  6_Fieldwarden
    bgname = Fieldwarden
    blurb = Protectors of the harvest, defense against pests, thieves, and beasts. A position of great honor, while it lasts: many guardians do not live out their natural lives. Roll a second time on the <b>Bonds</b> table.
    name = {Seed|Thresh|Dibber|Sow|Stalk|Harrow|Cobb|Flax|Briar|Rye}
    event1 = <b>What got the better of you?</b><br>{A voracious swarm of pests that swallowed crops and animals alike. With nothing to defend, you left. Take <b>Gale Seed Extract</b> (3 uses). Ingesting it lets you sprint with a speed four times your regular rate. Afterward you add two <b>Fatigue</b>.|A crop spirit, angered by a poor tithing. The fires consumed nearly everything, and afterward you were able to gather a pouch of <b>Fireseeds</b> (d8, <a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#attack-modifiers" target="_blank"><i>blast</i></a>, 4 uses).|An antlered, toothy demon that nearly ended you. Take a blood-stained <b>Bone Knife</b> (d6). On <a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#critical-damage" target="_blank"><b>Critical Damage</b></a>, its next attack becomes <a href = "https://cairnrpg.com/second-edition/players-guide/core-rules/#attack-modifiers" target="_blank"><i>enhanced</i></a> from contact with blood.|<i>The Withering</i>, a type of stem rot from the <b>Roots</b>. Take a <b>Diseased Crop</b> (6 uses) that quickly decays any plant it touches.|Wolves, or so you thought. You are now a <a href="https://cairnrpg.com/second-edition/wardens-guide/bestiary/#werewolf" target="_blank"><b>Werewolf</b></a> (8 HP, 15 STR, 14 DEX, claws (d6+d6), bite (d8)). Your WIL remains the same. You can <i>turn</i> at will (once per day) but must make a WIL save to revert. Anyone left alive from your attacks must make a WIL save to avoid infection.|Crop thieves. Not all of them survived, but you were outnumbered. Start with +d4 HP and a <b>Cusped Falchion</b> (d8).}
    event2 = <b>What tool saved your life?</b><br>{<b>Bloodvine Whip</b> - d8 damage. On <a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#critical-damage" target="_blank"><b>Critical Damage</b></a>, it drains the target’s blood, granting the weapon’s next attack the <a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#attack-modifiers" target="_blank"><i>blast</i></a> quality|<b>Clatter Keeper</b> - A hand-cranked device that emits a loud noise, frightening away most creatures.|<b>Sun Stick</b> - Provides ample warmth and light for up to one hour. <b>Recharge:</b> Leave in heavy sunlight for a full day. 1 use.|<b>Root Tether</b> - When thrown, binds a creature as large as a wolf to the soil for a short time.|<b>Greenwhistle</b> - A small flute that calms plants, making passage through areas heavy with plant life a bit easier.|<b>Everbloom Band</b> - A circlet adorned with flowers that never wilt. On <a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#critical-damage" target="_blank"><b>Critical Damage</b></a>, the flowers dissolve into dust, but you act as if your save succeeded (STR loss still occurs).}
    equip = Torch (3 uses)<br>Brigandine (1 <a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#armor" target="_blank">Armor</a>, <i>bulky</i>)<br>Sling (d6)<br>Hand Axe (d6)<br>Repellent (pick the type, 3 uses)
  
  7_Fletchwind 
    bgname = Fletchwind
    blurb = You strike from afar, but that does not make you a coward. You are a musician, the song of your bowstring nought but a warning, singing the silent promise of a quick death.
    name
      Feather
      Crier
      Thunder
      Falcon
      Pluck
      Needle
      Warsong
      Hawk
    event1 = <b>How did you earn your bow?</b><br>{<b>War</b> - If you are first to attack, your bow gains the <a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#attack-modifiers" target="_blank"><i>blast</i></a> property for the first round.|<b>Falconry</b> - You keep a falcon (3 hp, 5 STR, 16 DEX, 4 WIL, claws (d6+d6), bite (d8)). It only eats live game.|<b>Hunting</b> - When taking the <b>Supply</b> action, your ability to secure <b>Rations</b> increases by one step (e.g. 1d4 becomes 1d6).|<b>Tournaments</b> - Attacks with your bow are <a href = "https://cairnrpg.com/second-edition/players-guide/core-rules/#attack-modifiers" target="_blank"><i>enhanced</i></a> if the target is immobile.|<b>Training</b> - If you are the first to attack, melee attacks against you are <a href = "https://cairnrpg.com/second-edition/players-guide/core-rules/#attack-modifiers" target="_blank"><i>impaired</i></a> until you take STR damage.|<b>Scouting</b> - When taking the <b>Travel</b> action, your presence decreases the chance of getting lost by one step (e.g. 4-in-6 becomes 3-in-6).}
    event2 = <b>What kind of wood is your bow made from?</b><br>{<b>Western Yew</b> (d6, <i>bulky</i>). Can be wielded as a blunt weapon (d6). Noisy.|<b>Sessile Oak</b> (d8, <i>bulky</i>). Slams into targets. On <a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#critical-damage" target="_blank"><b>Critical Damage</b></a> something is torn off.|<b>Stone Pine</b> (d6, <i>bulky</i>). Produces one use of <b>Sticky Sap</b> per day. The sap is highly explosive.|<b>White Ash</b> (d6, <i>bulky</i>). Can be used in place of a shield in melee combat (+1 <a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#armor" target="_blank">Armor</a>).|<b>Striped Bamboo</b> (d6). Collapsible, it only requires one slot (but still requires both hands).|<b>Wych Elm</b> (d6, <i>bulky</i>). Protects the bearer from poisons and toxins, so long as they are holding it.}
    equip = Torch (3 uses)<br>Bow (see above)<br>Serrated Knife (d6)<br>Boiled Leather (1 <a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#armor" target="_blank">Armor</a>)<br>Heartroot Salve (restores 1d4 STR, 1 use)
  
  8_Foundling
    bgname = Foundling
    blurb = An odd birthmark, a strange smell: somehow, the touch of elsewhere still lingers. Wherever you are, you have trouble fitting in. Roll on the Omens table (even if you’re not the youngest player), but keep the results private for now.
    name = {Faunus|Snowdrop|Wisp|Silverdew|Brim|Solstice|Steeleye|Artea|Gossamer|Hazel}
    event1 = <b>Who took you in?</b><br>{An old hunter. You were both quite happy, until it all ended. Take a <b>Weathered Longbow</b> (d8, <i>bulky</i>) and a <b>Leather Jerkin</b> (1 <a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#armor" target="_blank">Armor</a>).|A wizened apothecary, who taught you the healing arts but maintained a clinical detachment. Take a <b>Healing Unguent</b> (restores d4 STR, 1 use).|A druid, who taught you the language of trees. When it came time to, you took with you only a <b>Gnarled Staff</b> (d8) and left a promise that one day you would return.|A gruff blacksmith from a sleepy river town. You were always kept at arm’s length. Now the forge is cold, and you’ve moved on. Take a <b>Smith’s Apron</b> (<i>petty</i>) and a set of <b>Oft-mended Chain Mail</b> (2 <a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#armor" target="_blank">Armor</a>, <i>bulky</i>).|A troupe of traveling entertainers. For a time, they were like family to you. One day you woke up and they were gone with no explanation. Take a <b>Storybook</b>, a <b>Dagger</b> (d6), and some burning questions.|The monks of a secluded forest monastery. When their rules became too strict, you snuck away. Take a <b>Monk’s Habit</b> (warm, <i>petty</i>) and a <a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#spellbooks" target="_blank"><b>Spellbook</b></a> of <i>Control Plants</i>. Control Plants: Nearby plants and trees obey you and gain the ability to move at a slow pace. <i>Leaves grow along the spine, and it smells faintly of decay.</i>}
    event2 = <b>What keeps bad tidings at bay?</b><br>{<b>Pipeweed</b> - Your good luck charm. Conversations tend to flow more easily after a smoke. 6 uses.|<b>Stink Jar</b> - Shattering this jar releases an odor so foul all nearby must make a STR save or immediately vomit. 1 use.|<b>Ivy Worm</b> - A green worm often mistaken for a weed. Swallowed whole, it absorbs any toxins or rot in the body before exiting through the usual way.|<b>Dream Stone</b> - A smooth blue stone that helps recall dreams more clearly. Overuse can cause dream-addiction.|<b>Drowning Rod</b> - A finger-sized wooden stick that doubles in size each time it is fully submerged in water. It does not shrink down again.|<b>Rabbit’s Foot</b> - You were wearing it when they found you. They say it is the foot of she who left you and that it protects you from witch magic. <i>Petty</i>.}
    equip = Torch (3 uses)<br>Salt Pouch<br>Heirloom Amulet (<i>petty</i>, glows in the presence of magic)<br>Sling (d6)<br>Dagger (d6)

  9_Fungal Forager
    bgname = Fungal Forager
    blurb = You follow the whisperings of the deep earth, the rhythmic pulse of the mycelium forest that grows beneath the surface. The dark holds no terror for you. Also, you really love mushrooms.
    name = {Unther|Woozy|Hilda|Current|Leif|Ratan|Mourella|Lal|Per|Madrigal}
    event1 = <b>What strange fungus did you discover?</b><br>{<b>Shrieking Trumpet</b> - When exposed to light, it screams so loudly that all nearby attacks (including your own) are <a href = "https://cairnrpg.com/second-edition/players-guide/core-rules/#attack-modifiers" target="_blank"><i>impaired</i></a>. 2 uses.|<b>Torch Fungus</b> -  When crushed, it creates a cold blue light for a short while. 2 uses.|<b>Murderous Truffle</b> - Pungent, highly toxic, and very rare (worth 50gp to assassins). Illegal pretty much everywhere. 1 use.|<b>Hellcap</b> - Exposure to its aroma causes intense nausea and vomiting. Either way, it clears the room. Bottled (1 use).|<b>Sproutcup</b> - Ingest to shrink down to the size of a mouse. (Your belongings stay the same size.) You return to normal size within the hour, often in fits and starts. 1 use.|<b>Rootflower</b> - A white fungus found only on corpses deep underground. Ingest to restore d6 WIL. You will dream of the dead and their stories. 1 use.}
    event2 = <b>What keeps you sane, even in utter darkness?</b><br>{<b>Glowsnail</b> - Casts a soft, bioluminescent light. Feeds on one ration every two days.|<b>Silk Moth Shawl</b> - A weatherproof blanket, it can also douse a fire without being damaged.|<b>Milkflower</b> - A gentle stimulant. Chewing it makes you immune to panic for the next hour. 3 uses.|<b>Luxcompass</b> - Hums softly as it moves closer to the Sun. Eventually the noise becomes unbearably loud.|<b>Sloth-Tarp</b> - A tough and weatherproof fabric, useful for hanging off trees. When inside, you have +1 <a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#armor" target="_blank">Armor</a>.|<b>Miner’s Grease</b> - Great for dislodging a gem, tool, or limb from a tight crack. Highly explosive. 3 uses.}
    equip = Sharpened Trowel (d6)<br>Candle Helmet (+1 <a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#armor" target="_blank">Armor</a>, dim, 6 uses)<br>Rope (25ft)<br>Metal Pail
  
  10_Greenwise
    bgname = Greenwise
    blurb = You delve deep into the Wood, prying its secrets from between rough boughs and whispering leaves. To this verdant kingdom, you are no mere scholar but its confidant as well.
    name
      Gunther
      Moss
      Fern
      Lichen
      Root
      Willow
      Sage
      Rowan
      Ash
    event1 = <b>How has the Wood failed you?</b><br>{An ill-tempered forest spirit cursed you for stealing, marking you as an enemy of their kind. Take a <b>Bezoar Stone</b>. Ingesting it cures any poison (1 use, unless retrieved).|A close friend disappeared into the forest. Now you see their face in any tea you brew. Take a <b>Soporific Concoction</b> (3 uses).|You were poisoned, losing your sense of taste and smell. You can now withstand noxious fumes and always carry <b>Antitoxin</b> (2 uses).|Your radical experiments turned your skin green, and you now gain nourishment as a plant. You don’t need <b>Rations</b>, but a day without sufficient sunlight and water leaves you <a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#deprivation--fatigue" target="_blank"><i>deprived</i></a>.|Your impressive corpseflower won a local contest then promptly killed a judge. You fled, but not without the <b>Prize Money</b> (100gp) and a warrant for your arrest.|You created a restorative tincture that also causes accidental infertility. Take a <b>Healing Potion</b> that completely restores STR. Only you know of its unintended side-effects.}
    event2 = <b>What keeps you safe while in the Wood?</b><br>{<b>Amadou</b> - A vermilion fungus that catches fire quite easily. 3 uses.|<b>Delphinium</b> - Breathe water for up to one hour. 1 use, but can be divided into fractional doses.|<b>Tacky Stalk</b> - A woody reed that hardens into a permanent adhesive when chewed. 2 uses.|<b>Wisp Lantern</b> - Caged in wrought iron, provides a dim light so long as the wisp is able to feed on nearby pain and fear.|<b>Seed Bomb</b> - A canvas sack filled with seeds that explode on impact. d6 damage (<a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#attack-modifiers" target="_blank"><i>blast</i></a>, 3 uses).|<b>Briarvine</b> - Entangles any creature up to horse size (STR to break free). Reusable.}
    equip = Torch (3 uses)<br>Iron Pot<br>Root Knife (d6)<br>Healing Salve (restore 1d4 STR, 1 use)<br>Twine Bauble (<i>petty</i>, Ward once per day) <i>Ward</i>: A silver circle 50ft across appears on the ground. Choose one species that cannot cross it.
  
  11_Half-Witch
    bgname = Half-Witch
    blurb = Born of both the mortal world and the unseen, you are an enigma to some and feared by many. Yours is the tale of what happens when two worlds collide.
    name = {Solena|Veles|Bryn|Sabine|Razvan|Rowena|Galen|Nyx|Vex|Iwan}
    event1 = <b>What did you bring back from the Unseelie Court?</b><br>{A <b>Black Rose Fiddle</b> (<i>bulky</i>) - Its music causes intense sadness and immobility in nearby mortals. (Others are merely fascinated.) You don’t know how to play.|<b>Paper legs</b> - You are extremely light, and can fall a few stories without getting hurt. Try to avoid tearing them or getting them wet.|A <b>Living Nightmare</b> that dwells within you but manifests whenever you are in danger. It has your same Attributes and HP and attacks with claws (d8+d8). It disappears on <a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#critical-damage" target="_blank"><b>Critical Damage</b></a> (take 1d4 WIL damage), re-appearing again on the next full moon.|A <b>Raven Familiar</b> (8 HP, 3 STR, 11 DEX, 13 WIL, beak, (d6)). It speaks as an intelligent being and is entirely devoted to you.|A <b>Briar Thorn</b>. It can pierce any organic material (quite painfully) but when removed leaves no trace of the intrusion.|A Fae creature’s <b>True Name</b>. Use it to summon its owner for an act of great service, but only once. It could also fetch a hefty price, from the right buyer.}
    event2 = <b>What concoction do you carry, and what rare ingredients did you gather to make it?</b><br>{<b>Rebirth Ash</b> - Remnants of a bark spirit. Sprinkle to reignite a fire that has died or return to life a creature that has died only moments before. 3 uses.|<b>Glamour Feather</b> - Plume of a firebird. Can make any creature appear convincingly as someone (or something) else. 1 use.|<b>Hawthorn Seed</b> - An acorn from the other side, gathered on the spring equinox. When planted, it sprouts a luxurious shelter, collapsing at moonrise the next day. 1 use.|<b>Stonetree Sap</b> - Sap obtained in exchange for blood. Hardens when rubbed on any surface (+1 <a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#armor" target="_blank">Armor</a>). 3 uses.|<b>Nightdust Powder</b> - Made from the ritual burning of six owls. When tossed in the air, day turns to night for a short while. 2 uses.|<b>Hex Stone</b> - Gathered from a river that flows from the other side. Removed from its iron tin, it can absorb the effects of an active magical effect. If destroyed, the magic is released. 1 use.}
    equip = Torch (3 uses)<br><a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#spellbooks" target="_blank">Spellbook</a> (Thicket: A thicket of trees and dense brush up to 50ft wide suddenly sprouts up. <i>Wrapped in vines that must be destroyed again with each use.</i>)<br>Iron Dagger (d6)<br>Herbs Pouch (restore 1 STR, 3 uses)<br>Ghillie Suit
  
  12_Hexenbane
    bgname = Hexenbane
    blurb = You are a mere digit on the unerring hand of justice. You go where others fear to tread, unyielding and unbroken.
    name
      Percival
      Felix
      Isolde
      Wolfram
      Aldric
      Eira
      Ivor
      Brunhilda
      Beatrix
    event1 = <b>To which order do you belong?</b><br>{<b>Order of the Crossroads</b> - Take a <b>Pocket Leyfinder</b>. It points to nearby ley lines and other sources of arcane power. If you lose it, the punishment is death.|<b>Order of the Bleeding Star</b> - Take a <b>Star-Iron Mace</b> (d8). It shines faintly in darkness and becomes very hot in the presence of witchcraft.|<b>Order of the Glass Sigil</b>. Take a <b>short sword</b> (d8) and <b>chainmail</b> (2 <a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#armor" target="_blank">Armor</a>, <i>bulky</i>). You have contacts in most towns (the more rural, the better) willing to provide aid, food, or even weapons.|<b>Order of the Blank Eye</b>. Take a <b>Voidglass Shard</b>. Peer through it to see invisible marks, creatures, and other magical effects. Lose the use of your eye for an hour afterwards (you are <a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#deprivation--fatigue" target="_blank"><i>deprived</i></a>).|<b>Order of Canaas</b> - Once per day, you can change into a wolf. Take a <b>Quicksilver Chain</b>. Without it, you are unable to shift back.|<b>Order of the Silent Veil</b> - Take a <b>Quell Stone</b> (2 uses) wrapped in burlap. Extinguishes any nearby flames once exposed to air.}
    event2 = <b>What was your vow?</b><br>{<b>Honesty</b> - Choose a weapon type (blunt, blade, etc). Attacks against you of this type are <a href = "https://cairnrpg.com/second-edition/players-guide/core-rules/#attack-modifiers" target="_blank"><i>impaired</i></a>. If your vow is broken, you lose d4 WIL.|<b>Poverty</b> - You carry the <i>Disassemble</i> <a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#spellbooks" target="_blank"><b>Spellbook</b></a>. Only you can use it. If your vow is broken, it explodes (d12 STR damage). Disassemble: Any of your body parts may be detached and reattached at will, without causing pain or damage. You can still control them. <i>Regenerates any torn or defaced pages.</i>|<b>Selflessness</b> - You are immune to mind-altering magical effects, such as charm, hatred, frenzy, and so on. If you break this vow, you lose d6 WIL.|<b>Mercy</b>. Choose a weapon type (blunt, blade, etc). Attacks with this weapon are <a href = "https://cairnrpg.com/second-edition/players-guide/core-rules/#attack-modifiers" target="_blank"><i>enhanced</i></a>. If your vow is broken, you can never use that weapon type again.|<b>Charity</b>. Once per day you can shrug off a <b>Fatigue</b>. If your vow is ever broken, you permanently lose one inventory slot.|<b>Valor</b>. The first time you inflict <a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#critical-damage" target="_blank"><b>Critical Damage</b></a>, you receive +d4 HP, returning to the previous limit at the end of combat. If your vow is broken, you die.}
    equip = Torch (3 uses)<br>Vestments of the Order (<i>petty</i>)<br>Blessed Tinctures<br>Silver Knife (d6)<br>Crossbow (d8, <i>bulky</i>)
  
  13_Jongleur
    bgname = Jongleur
    blurb = What inspires the soul more than song, words, and spectacle? Why practice for years to master the arcane when you’ve already got real magic inside?
    name = {Jax|Selene|Baladria|Ada|Mort|Saylor|Tripp|Lantos|Echo|Jubilo}
    event1 = <b>What happened at your final performance?</b><br>{Despite your training in the deadly arts, an actor died and you were blamed. Take a light-weight <b>Rapier</b> (d6) and a false identity.|The crowd loved your catchy tune about a noble and his romantic failings. The noble in question, not so much. Take the <i>Read Mind</i> <a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#spellbooks" target="_blank"><b>Spellbook</b></a> and a warrant for your arrest. Read Mind: You can hear the surface thoughts of nearby creatures. <i>Long-term possession can cause the reader to mistake the thoughts of others as their own.</i>|Your debut composition reduced the audience to a gibbering mess, murmuring of bright creatures descending from the night sky. Later you noticed that the notes resembled stellar constellations. Take a <b>Book On Astronomy</b>, and a lot of questions.|You mocked a forgotten trickster god and were cursed for it. You speak only in perfect rhyme. Ironically, this has only made you more popular among your peers. Take a <b>Thesaurus</b> (20gp). Without it, you are <a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#deprivation--fatigue" target="_blank"><i>deprived</i></a>.|You were scarred in an on-stage accident. The crowd cheered, thinking it was part of the act. Take well-worn <b>Stage Mail</b> (1 <a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#armor" target="_blank">Armor</a>), a memorable scar, and a fear of applause.|Your respectable puppeteering skills were matched only by your mimicry. You were so good you were branded a witch (literally) and banished. Take an <b>Uncanny Hand-Puppet</b> and a <b>Rabbit Skull</b> (<i>petty</i>) that protects against charms.}
    event2 = <b>What trinket were you unable to leave behind?</b><br>{<b>False Cuffs</b> - Comfortable, realistic-looking cuffs. Only you know the trick to get out of them.|<b>Pocket Theatre</b> - A set of small puppets and a folding stage. Good for quick distractions.|<b>Ghost Violin</b> - A dark-gray violin that plays a haunting tune, mirrored by an invisible, distant twin.|<b>Tragic Tales</b> - Banned in proper company, this book becomes less bawdy and more harrowing towards the end. Worth 100gp.|<b>Mythos Mask</b> - A plaster mask that allows one to take on a monster’s countenance. Once it comes off, add a <b>Fatigue</b>.|<b>Rebreak Glass</b> - A wine flute that can be broken multiple times, reforming after 24 hours. Makes a really loud noise.}
    equip = Torch (3 uses)<br>Costume<br>Simple Instrument (Pipes, Lute, etc.)<br>Lucky Jerkin (+1 <a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#armor" target="_blank">Armor</a>)<br>Sling (d6)
  
  14_Kettlewright
    bgname = Kettlewright
    blurb = You are known by the smell of molten metal and the jingle of tin. You are no mere merchant but an artisan of fire and metal.
    name = {Fergus|Eon|Bram|Idris|Hester|Darragh|Seren|Rónán|Berek|Lorenz}
    event1 = <b>What is your trade?</b><br>{You build small contraptions for local guilds (and don’t ask too many questions). Take an extra 40gp and a wanted poster with your face on it. Given time and materials, you can open almost any door or vault.|You deal in home goods and tools, hawking your wares to townspeople across the lands. Take 20gp worth of items from the <a href="https://cairnrpg.com/second-edition/players-guide/marketplace/#gear" target="_blank">gear table</a>. You are fluent in the <i>Traveler’s Cant</i>.|You were a military smelter, before peace destroyed your livelihood. Take a <b>smelting hammer</b> (d10, <i>bulky</i>) and a <b>tin helm</b> (+1 <a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#armor" target="_blank">Armor</a>). Given time and adequate materials, you can repair armor.|You sell rare and quality items to monasteries and nobles alike. Take a <b>Spyglass</b>, a <b>Necklace</b> (<i>petty</i>) worth 20gp, and a <a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#scrolls" target="_blank"><b>Scroll</b></a> of Mirrorwalk (<i>petty</i>).|You offer protection as a service, quietly watching for threats as money exchanges hands. You start with an extra [hp=dfour.selectOne] HP, and carry a <b>Long Sword</b> (d10, <i>bulky</i>) and a <b>Gambeson</b> (+1 <a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#armor" target="_blank">Armor</a>).}
    event2 = <b>What never fails to get you out of trouble?</b><br>{<b>Fire Eggs</b> - Six small pellets made of sea salt, wood, and crockery-dust. They explode at low heat (d8, <a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#attack-modifiers" target="_blank"><i>blast</i></a>) but the flames dissipate quickly.|<b>Black Tar</b> - Versatile: both sticky and highly flammable. 3 uses.|<b>Spiked Boots</b> - Cracks heads (d8) as easily as it does ice and muck. Travel is also a bit slower, but easier.|<b>Tinker’s Paste</b> - Seals shut any fist-sized opening. 3 uses.|<b>Fireworks</b> - A dazzling albeit dangerous display. Enough explosive material to blow off a finger or three. 2 uses remain.|<b>Carrion Cat</b> - A clever pet, small enough to hide in your pack (<i>bulky</i>), but strong enough to scare off smaller predators. Requires one Ration a day, and it must be meat.}
    equip = Torch (3 uses)<br>Pincers<br>Roll of Tin<br>Gloves (<i>petty</i>)<br>Hammer (d6)
  
  15_Marchguard
    bgname = Marchguard
    blurb = Bound by blood Oath to patrol the border and protect the realm. Once sworn, the Oath cannot be broken. The Guard always finds their own.
    name = {Gann|Light|Saoirse|Frost|Thorn|Reed|Dirk|Ragnar|Brie|Aasim}
    event1 = <b>Why did you take the Oath?</b><br>{Your family has a long tradition of serving, and you were trained from an early age on how to survive in the wild. When taking the Supply action, your yield increases by one step (e.g. 1d4 > 1d6).|As a convict, the Oath was simply a means of avoiding punishment. Take a set of <b>Lockpicks</b> and the <b>Key</b> (<i>petty</i>) to a safehouse.|Noble-born, you joined to escape family trouble. Take a <b>Goosefelt Tarp</b> (fits two) that you stole before leaving home.|When your family lost everything, you took the Oath to avoid becoming a burden. Take extra <b>Rations</b> (3 uses) and a brace of <b>Throwing Knives</b> (d6).|Your life was saved by a member of the Marchguard, and you were inspired to join their ranks. Take a <b>Snare Trap</b> and a <b>Sketchbook</b> filled with detailed drawings.|You were in a dark place and decided that your life needed a little direction. You’re still not so sure it was the right choice. Take an <b>Oilskin Coat</b> and <b>Mapping Paper</b>.}
    event2 = <b>What do you carry as proof of your Oath?</b><br>{<b>Impressive Pin</b> - A metal badge of honor from the Guard. It can open doors but leaves a trail. <i>Petty</i>.|<b>Oath Compass</b> - Points not towards North, but instead to the nearest member of the Guard. It also lets you know when they’re getting close.|<b>Pullstones</b> - Two jet-black stones. When separated, the stones will always roll toward one another.|<b>Fireflask</b> - Highly alcoholic, yet strangely delicious. When thrown, it creates a wall of flames 10ft high that burns out after a few minutes. 1 use.|<b>Pain Band</b> - Touch an injured creature to transfer their wounds to you. (Exchange their lost STR with your own.) Recharge: Wear the ring while in perfect health. You will lose 1 STR, permanently. <i>Petty</i>.}
    equip = Lantern<br>Oil Can (6 uses)<br>Long Sword (d10, <i>bulky</i>)<br>Boiled Leather (1 <a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#armor" target="_blank">Armor</a>)<br>
  
  16_Mountebank
    bgname = Mountebank
    blurb = Wits are your sharpest weapon, a facade your strongest shield. But when you do lose, you lose badly.
    name 
      Ambrose
      Lucius
      Beauregard
      Cornelius
      Aria
      Toph
      Delphine
      Solene
      Noa
    event1 = <b>How was your fraud exposed?</b><br>{Your “patients” kept reporting miraculous recoveries, despite your lack of training. Start with <b>Bandages</b> (3 uses) and a knack for healing.[addomn=0,""]|After seducing a wealthy patron, their family hired a criminal gang to retrieve you. You got away and need to lay low. Start with <b>Beauty Cream</b>, 2 uses. Apply to appear irresistibly beautiful for the next 12 hours.[addomn=0,""]|You were a peddler of fake prophesies, but when one turned out to be true, it drew unwanted attention. Roll on the Omens table, but keep the result to yourself. Start with a concealable Knife (d6, <i>petty</i>).[addomn=1,""]|Your latest stunt destroyed a priceless artifact and injured a dozen bystanders. Start with a <b>Captain’s Uniform</b> (<i>petty</i>), a <b>Ceremonial Sword</b> (harmless, 60gp), and a <b>Bouquet of Flowers</b>.[addomn=0,""]|You were cursed by a hedgewitch for fooling some innocent village folk. Magic acts unpredictably in your hands (WIL save to avoid disaster). If you are the target of magic, the same applies to its wielder.[addomn=0,""]|Your “seances” with the dead were in actuality a ruse involving a cleverly hidden <a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#spellbooks" target="_blank">spellbook</a> of Auditory Illusion. Inevitably, a patron discovered your secret. Start with the <a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#spellbooks" target="_blank"><b>Spellbook</b></a> and a bundle of scarves. Auditory Illusion: You create illusory sounds that seem to come from a direction of your choice.[addomn=0,""]}
    event2 = <b>What keepsake could always identify you?</b><br>{<b>Royal Crest</b> - Born into royalty, you chose a different life. The crest grants you access but also alerts your family of your whereabouts. <i>Petty</i>.|<b>Miracle Oil</b> - A smelly, slippery concoction. 2 uses.|<b>Surgeon’s Soap</b> - A lye and ash block that makes skin temporarily transparent, revealing the anatomy within. 4 uses.|<b>Goat Powder</b> - Derived from the placenta of a baby goat. Temporarily cures any affliction, but symptoms return within hours.|<b>Cursed Sapphire</b> - Worth 200gp, it noticeably returns to your pocket shortly after you spend it. You can’t seem to get rid of it.|<b>Alchemical Tattoo</b> - A dog, cat, or bird that can leave your body on demand. It follows your commands to the best of its abilities and can pass its injuries (as STR loss) back onto you. <i>Petty</i>.}
    equip = Torch (3 uses)<br>Cart (+4 slots, <i>bulky</i> when pulled)<br>Trick Playing Cards<br>Fancy Hat (<i>petty</i>)<br>Cane Sword (d6)
  
  17_Outrider
    bgname = Outrider
    blurb = Your coin comes from escorting caravans, tracking fugitives, or lending your blade to a cause. You’ve been a savior, an executioner, a hero, and even a villain. Yours is not a solitary path, however: you’ll always have your horse.
    name
      Cyra
      Keir
      Darius
      Valen
      Rorik
      Yara
      Rui
      Talon
      Jory
    event1 = <b>What personal code or principle do you uphold?</b><br>{<b>No innocent blood:</b> [addbnd=0,""]No bystander will come to harm on your watch. Take a <b>Steadymade Buckler</b> (+1 <a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#armor" target="_blank">Armor</a>). While holding this shield, you cannot be moved so long as both feet are planted on firm ground.|<b>Revere the tools of death:</b> [addbnd=0,""]Weapons are to be respected and maintained. Take a <b>Wyrmbone Whetstone</b>. Following a half-hour ritual sharpening, attacks with the weapon are <a href = "https://cairnrpg.com/second-edition/players-guide/core-rules/#attack-modifiers" target="_blank"><i>enhanced</i></a> until STR damage is dealt.|<b>To the death, always:</b> [addbnd=0,""]You never back down from a fight, no matter the odds. Take a <b>Death-Whistle</b>, 1 charge. Its scream frightens away all who hear it (save WIL or flee). <b>Recharge:</b> Capture the final breath of a dying warrior.|<b>Revere the dead:</b> [addbnd=0,""]Death is a journey we all take, and it deserves respect. Take an extra 30gp. You always place two gold pieces on the eyelids of a slain foe. Somehow, you always find the coin.|<b>Loyalty to the work:</b> [addbnd=0,""]Your word is your bond. Once you’ve accepted a job, you see it through to the end. Take a weathered <b>Tally Stick</b>. Once a vow is marked onto its face, the stick hardens (d8) until it is complete. The stick will snap in half if the vow is ever broken.|<b>Always pay your debts:</b> [addbnd=1,""]You always repay what you owe, whether in coin or in kind. You expect nothing less from all others. Take a <b>Blacked-Out Ledger</b>. Roll a second time on the Bonds table.}
    event2 = <b>What breed is your horse?</b><br>{<b>Heavy Destrier</b> - A beast built for war, an imposing creature. 8 HP, 1 <a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#armor" target="_blank">Armor</a>, hooves (d10+d10), +2 slots.|<b>Blacklegged Dandy</b> - Hardy and adaptable. <b>Tough</b> or <b>Perilous</b> terrain are one step easier. 6 HP. +4 slots.|<b>Rivertooth</b> - Impressively strong, capable of carrying heavy loads. 4 HP. +6 slots (only +2 slots if carrying two people).|<b>Piebald Cob</b> - Intelligent, it can understand simple commands and even has an instinct for danger. 6 HP. +4 slots.|<b>Linden White</b> - Highly trained and agile, it can perform intricate maneuvers in a time of need (no DEX save to flee). 4 HP. +3 slots.|<b>Stray Fogger</b> - Wild but very fast (even in <b>Tough</b> terrain). Rides light. 4 HP. +2 slots.}
    equip = Torch (3 uses)<br>Long Sword (d10, <i>bulky</i>)<br>Leather Jerkin (1 <a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#armor" target="_blank">Armor</a>)<br>Crossbow (d8, <i>bulky</i>)<br>Spyglass
  
  18_Prowler
    bgname = Prowler
    blurb = You are a specter in the night, a fleeting shadow that slips by its prey, unseen. Each kill is a test of cunning and animal determination, a contest between life and death. You know that one day you will lose. You look forward to it.
    name = {Winda|Brielle|Theron|Chayse|Nuja|Dev|Raven|Arawan|Sable|Baruani}
    event1 = <b>What did you last hunt?</b><br>{A <i>mock firefly</i>, baiting water carriers with its glowing lure. Take an <b>Alchemical Limb</b> (d8, <i>petty</i> when worn) to replace the one it tore off and an <b>Oil Can</b> (6 uses). The limb is immune to heat and poison. Needs to be oiled daily.|An <i>ice nettle</i>, trapping and draining sheep. You lost your commission when the fungus you introduced killed half the flock. Take a <b>Rime Seed</b> (1 use). It freezes any body of water, no matter the size. Don’t eat it.|A <i>silver marsh crawler</i> that killed someone close to you. You now carry its <b>Tooth</b> (<i>petty</i>) on a chain around your neck as a warning to others of its kind. <i>The tooth hums softly when something is stalking you</i>.|A malicious <i>forest spirit</i> that poisoned a homestead. You saved a <b>Heartseed</b> from the roots of a dying tree. (Plant it to create a new forest.) Also, take <b>Iron Bracers</b> (+1 <a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#armor" target="_blank">Armor</a>, <i>bulky</i>).|A <i>hollow wolf</i> that had been frightening travelers. You took pity on the half-starved creature and nursed it back to health. Now it is loyal to you unto death. It is also a great tunneler. 5 HP, 11 STR, 13 DEX, 8 WIL, teeth (d6).|An <i>azure warbler</i>. The gametes attract a sizeable profit, if properly extracted. You succeeded but left its nest to the wolves. Take a <b>Paring Knife</b> (d6), an extra 20gp, and a pang of regret.}
    event2 = <b>What tool is always in your pack?</b><br>{<b>Fermented Spirits</b> - Keeps you warm at the best of times and as an explosive at the worst. 3 Uses.|<b>Trail Shaker</b> - A noisy instrument that reveals nearby trails, even when deeply hidden.|<b>Drowse Balm</b> - A wax bar. If boiled in water, the steam acts as a soporific agent.|<b>Spike and Cord</b> - For traversing difficult terrain or for creating makeshift traps and structures.|<b>Iron Rattle</b> - A noisemaker for distracting or scaring your quarry. Sounds convincingly like a snake.|<b>Hardening Glue</b> - Makes any flat material (cloth, leather, sand) as hard as stone. Expensive (20gp a bottle, 3 uses).}
    equip = Torch (3 uses)<br>Tarp<br>Boiled Leather (1 <a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#armor" target="_blank">Armor</a>)<br>Short Sword (d6)<br>Spring-Loaded trap (4 STR damage)
  
  19_Rill Runner
    bgname = Rill Runner
    blurb = You sing the stories of rivers and lakes, your talents soothing friends and the elements alike. You’ve seen more than most, but somehow it never seems to be enough.
    name
      Gale
      Piper
      Brook
      Adair
      Dale
      Wren
      Cliff
      Rain
      Robin
    event1 = <b>What songs are you best known for?</b><br>{<i>The Tinker’s Two-Step</i>. A humorous fairy tale about a gift-giving traveler. Start with a <b>Reed Whistle</b>. Anyone in earshot must pass a WIL save to perform an act of violence.|<i>The Sylph and Her Lover</i>. A bawdy tale of lost love. Start with a <b>Breeze Knot</b> (3 charges). Creates a strong breeze. <b>Recharge</b>: Tie it to a mast during a storm.|<i>Harper’s Devotion</i>. A sad, short tale about a musician that falls in love with a star. Start with a <b>Celestial Lute</b>. Reveals the constellations above, no matter the weather.|<i>The Reed Fisher</i>. A celebrated song about a massive carp that always seems to get away. Begin with a spool of <b>River Twine</b> (5 uses). Each dip into the river guarantees a catch, though it might not be pleasant.|<i>Song of the Silver Stream</i>. A wordless lullaby that mimics flowing water. Take a <b>Stone Flute</b> that can calm almost any river.|<i>The Thrush and the Meadow</i>. A moody tale told in alternating chorus. Start with a <b>Feather Quill</b> (1 use, <i>petty</i>). A map drawn with this quill reveals the most expedient course between any two points.}
    event2 = <b>What pays your way across the land?</b><br>{<b>Performance</b> - Performing at taverns always yields both room and board. Sometimes you even get tips! Start with an extra 10gp.|<b>Bodyguard</b> - You are a protector for those afraid to travel alone. Start with a <b>Rapier</b> (d8).|<b>Wares</b> - You buy low and sell high, always making just enough to get by. Take a single item worth 20gp (or less) from the <a href="https://cairnrpg.com/second-edition/players-guide/marketplace/#gear" target="_blank">gear table</a>.|<b>Transport</b> - You deliver “delicate” packages throughout the lands. You have at least one contact in any major town.|<b>Sailor’s Friend</b> - Over troubled waters and dangerous winds, you always make sure a ship reaches its destination. For you, passage is always free.|<b>Guide</b> - You shepherd caravans and travelers across water-soaked lands. Start a <b>map</b> (<i>petty</i>) relevant to your next journey.}
    equip = Torch (3 uses)<br>Water Shoes<br>Brigandine (1 <a href="https://cairnrpg.com/second-edition/players-guide/core-rules/#armor" target="_blank">Armor</a>, <i>bulky</i>)<br>Compass<br>Dagger (d6)
  
  20_Scrivener
    bgname = Scrivener
    blurb = You copy ancient texts and illuminate manuscripts, recording the voices of the clever, the great, and the powerful. You will prove that the pen truly is mightier than the sword.
    name
      Lazlo
      Stilo
      Akshara
      Pisa
      Ji-Yun
      Hugo
      Shui
      Kalam
      Julius
    event1 = <b>What work did you keep for yourself?</b><br>{<b>The Wild Tongue</b> A bundle of leather-bound scrolls. A seminal work, cataloging the hidden languages of beasts and how to understand them.|<b>The Silent Symphony</b> - Bound in fluorescent wrap. Very rare, it chronicles the subtle signs used by those employing invisibility magic.|<b>A Treatise on the Abyss</b> - A nondescript black book. An in-depth, largely theoretical text describing the <b>Roots</b>, as well as information about the location of a nearby <b>Gate</b>.|<b>The Star Waltz</b> - A comet-shaped clasp bound in a fine leather cover. Detailed astronomical charts, celestial movements, and stellar festivals. Highly valued (100gp) for its usefulness to travelers.|<b>The Cathedral and the Canopy</b> - Large-leaf binding over vellum. Nominally a children’s storybook, the margins detail information about traveling, eating, and sleeping in the cloud forests.|<b>Garden of Glass</b> - Bound in the cover of another book. A heretical work, it describes the materials, procedures, and optimal locations required to open a <b>Gate</b>.}
    event2 = <b>How do you transcribe sensitive information?</b><br>{<b>Fib Ink</b> - Glows when used to write true statements but fades if used to write false ones.|<b>Cipher Stone</b> - A pair of sharp black stones. Each one decrypts any message written by the other.|<b>Everquill</b> - A quill that writes on any surface. You still need ink. <i>Petty</i>.|<b>Whisper Vial</b> - Whisper a message into the vial, and it will play it back to whoever opens it next.|<b>Sanguine Lens</b> - Extracts blood from a target without their knowledge. A stolen drop placed on the eye reveals memories from the past day.|<b>Echo Leaf</b> - A blank parchment. Whomever unfurls it sees their actions of the day slowly revealed in a tight scrawl. <i>Petty</i>.}
    equip = Torch (3 uses)<br>Quill & Ink<br>Blank Book<br>Awl (d6)<br>Badge (<i>petty</i>)

physique
  athletic
  brawny
  flabby
  lanky
  rugged
  scrawny
  short
  statuesque
  stout
  towering

skin
  birthmarked
  marked
  oily
  rosy
  scarred
  soft
  tanned
  tattooed
  weathered
  webbed

hair
  no
  braided
  curly
  filthy
  frizzy
  long
  luxurious
  oily
  wavy
  wispy

face
  bony
  broken
  chiseled
  elongated
  pale
  perfect
  rakish
  sharp
  square
  sunken

speech
  blunt
  booming
  cryptic
  droning
  formal
  gravelly
  precise
  squeaky
  stuttering
  whispery

clothing
  antique clothing
  bloody clothing
  elegant clothing
  filthy clothing
  foreign clothing
  frayed clothing
  frumpy clothing
  livery
  rancid clothing
  soiled clothing

virtue
  ambitious
  cautious
  courageous
  disciplined
  gregareous
  honorable
  humble
  merciful
  serene
  tolerant

vice
  aggressive
  bitter
  craven
  deceitful
  greedy
  lazy
  nervous
  rude
  vain
  vengeful

bond
  You inherited a <b>Single Gem</b> (500gp, cold and brittle) from a long-dead relative. It arrived with a warning: squander your newfound riches and a debt long thought forgotten will be called in.
  A distant cousin left you a small inheritance. Take 20Gp and a <b>Strange Compass</b> (<i>petty</i>) that always points towards something deep in the Wood.
  You carry a <b>Portrait</b> in a locket (<i>petty</i>) of a past love who disappeared into the Wood long ago. Somehow you know that they are still alive.
  You found a <b>Tiny Crystal Prism</b> (<i>petty</i>) buried in the dirt. When held up to the light, it shows visions of an unknown location deep within the Wood. Sometimes you feel a presence looking back at you.
  You once freed a Naiad from a choked stream. In return, it gave you some <b>Silver Moss</b> (<i>petty</i>). Swallow it near water, and the creature will come, once, to repay its debt.
  You inherited an old <b>Journal</b>, bound in bark. Each evening, its pages are filled with the events of the day, crassly written from the journal’s perspective. The writing is crude but accurate.
  You protect a long-dormant family secret. Take one half of an <b>Ancient Key</b> (<i>petty</i>). They say that if joined with its twin, it opens a <b>Gate</b> through any door.
  You received a <b>Letter</b> (<i>petty</i>) detailing incontrovertible proof that your true parentage is that of Fae nobility. The note also indicates a date and location where you are to meet the letter’s author, deep in the the Wood.
  You owe a great debt to a member of the nobility and carry their <b>Signet Ring</b> (<i>petty</i>), which serves as proof of their protection as well as your obligation.
  You consumed a <b>Mischievous Spirit</b> that wreaks havoc on your insides, demanding to be taken home, deep in the Wood. It occupies one slot but absorbs one <b>Fatigue</b> each day. It wants you alive (for now).
  A roaming storyteller once spun you tales of great treasure hidden deep in the Wood. You thought it naught but fancy, till they gave you <b>A Rolled-Up Map</b> (<i>petty</i>) marked with an X.
  During your travels, you met a dying hunter who asked you to deliver a message to their loved ones. Take a <b>Letter</b> (<i>petty</i>), sealed with tree sap. It is addressed only to the <b>Lord Of Winter</b>.
  You found a wounded beast in the forest but chose to ignore it. You see it everywhere now, but only when you’re alone. It looks sad but not angry. You cannot become panicked when acting alone.
  You promised a childhood friend that you’d bring them back a rare gift, something unique in all the world. Take a <b>Bracelet</b> (<i>petty</i>) woven from twine and wildflowers.
  You crossed a creature of the Wood, and it cursed you with a <b>Stone Heart</b>. With each passing month, the stone grows heavier by one slot. Until your debt is lifted, you cannot truly die.
  You carved a <b>Whistle</b> (<i>petty</i>) from an <b>Oak Lord's</b> branch. Your act did not go unnoticed. You cannot seem to rid yourself of the whistle either.
  The <b>Dawn Brigade</b> did your family a service, giving you a dried <b>Blood-Red Flower</b> (<i>petty</i>) as proof. When the flower turns white, it means the favor is owed.
  An entertainer once visited your home, filling it with story and song. He left one day without a word, leaving behind only <b>A Miniature Lute</b>. Something rattles inside.
  A white crow appeared to you in a dream, holding a twig in its mouth. You awoke the next morning with the <b>Twig</b> (<i>petty</i>) in your hand. You believe it brings you luck. It smells faintly of sulfur.
  One of your ancestors wronged a <b>Moss Witch</b>, who cursed their bloodline. Your visage causes mirrors to shatter. You’ve noticed that the shards can sometimes reveal illusions.
