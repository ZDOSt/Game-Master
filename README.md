A SillyTavern Preset where the LLM acts as the Game/Dungeon Master, and you are the Player. The result of weeks of writing and rewriting rules over and over until I was satisfied. Also my very first contribution to the community. 
NOTE: This preset uses Marinara Spaghetti's layout as a base. It will look familiar. Full credits at the end :) 

PRESET: HOW IT WORKS
1. You send a message.
2. Custom CoT begins, where: 
   - LLM checks scene state, relevant history, who witnessed it, and whether present characters know it or not
   - Contextually determines if mechanics are necessary. IF YES: Runs mechanics from Lorebook to determine success/failure. (this actually changes narration afterwards depending on results)
   - Runs some checks from Lorebook to set initial NPC demeanor towards user (if new on scene) or check current NPCs. This step will also change demeanor based on user actions/dialogue. (prevents NPCs from falling in love with you instantly)
   - Runs a "Random Event Generator" to determine if a plot twist takes place (10% chance). 
   - NPC internal thoughts and planned response to user.
   - Pre-flight check: Rule reinforcement. Here, LLM is forced to fill in the blanks and recall rules.
3. LLM narrates, according to pre-established results/rules in preceding CoT.

LOREBOOK ENTRIES:
1. NPC Disposition: Determines how NPCs feel about your character. There are five stats: Fear, Hostility, Liking, Trust, Respect. Range is 0-6, where 3 is neutral (most common on meeting a new NPC). Without getting into too much detail: 
Initial Disposition: Depending on context. For example, my "half demon" character with horns and a tail often gets high Fear/Hostility (depending on NPC), low Trust/Liking. Respect is *independent* of other stats... even an opponent can respect you. 
Actions are divided into "Shallow" and "Meaningful". Talking, compliments, and just being... superficial, counts as shallow (with rare exceptions, depending on context). Liking/Trust cannot go past 4 through talking alone. To reachy 5 or 6, you need Meaningful actions across a few scenes (some actions, however, can skyrocket Liking/Trust, such as putting yourself in harm's way to save someone's life)
Repeated back to back shallow actions... can actually make NPCs dislike you.

2. Mechanics: A... very simplistic, yet highly condensed d20 ruleset. This is narrative-focused: There are no experience points, no HP, no skill points. There are four stats (for the sake of deciding outcomes), a single dice roll (d20), and some difficulty classes for environmental challenges. The goal was simple: To add a degree of unpredictability to roleplay.
3. Random Event Engine: Simply put... this will roll some dice in the background to decide whether a curveball will come your way. Most of the time it will do nothing (low chance), and narration will continue normally.
4. Character Creation: A crude character creator compatible with all of the above. This will roll some stats for you, and generate a completely random character. Crude is an understatement. It works, but I intend to make this better at some point. 
5. Game Start: Simply an instruction for the first initial scene. Personally, I like "isekai" or "reincarnation" stories, so this one is based off of that. 

WHAT TO EXPECT: 
1. Fairly good, almost slop-free writing. This preset targets not a few phrases, but the behaviors that cause crappy writing in the first place. Metaphors, hyperbole, simile, personification, are expressly banned and rarely make their way into a response. Blushing, reddening, eye darkening, flickering and... BS that you can't really see should happen much less often than usual, if at all. Scents/air taste (ozone, anyone? Air tastes like what?) must meet very strict guidelines for it to show up at all. The ENTIRE premise of this preset is: Show what can be PERCEIVED through the senses. 
2. NPCs that judge you based on appearance, and how you act or talk. They won't jump into your arms the moment you say something nice, and might even grow to hate you.
3. NPCs whose demeanor can change over time. Just because they like you now... doesn't mean they will later if you screw up.
4. Your actions can have consequences, and your success is not guaranteed (mechanics).
5. Unique Names! Elaras, Lyras, Miras, and Voss... BANNED. LLM will actively generate new names for locations/characters when needed.
6. Information stays hidden until revealed. And YES, this includes character names too! You will get things like "the guard" or "the innkeeper". Once their names are learned, then you will see them in chat.
7. A scene tracker that tracks relationship status, and... other information. If you use Marinara's tracker, you could disable this and save some tokens. You will have to modify the settings to make it compatible with this. 
8. Maybe more that I am forgetting?  

DON'T WANT MECHANICS? For general roleplay, do the following: 
1. Deactivate Ability Integration, NO Meta, Scene Tracker
2. Delete STEP 3 from CoT, and adjust numbering on the rest. Deactivate Mechanics lorebook entry. 
3. If you want to also remove Random Event Generator and Relationship Engine, delete STEP 4 and 5 in CoT, adjust numbering, and deactivate corresponding entries in Lorebook. 

NEGATIVES: 
1. This preset + lorebook will take around 10K tokens. It's about as short as I can make it right now, considering everything it achieves.
2. Generated message + Scene tracker will consume a lot of tokens. Disable Scene Tracker if you have another solution.  
3. It is certainly NOT perfect. LLMs are dumb things... IF the LLM makes a mistake, correct it right away. If you allow one mistake, LLM will keep doing it.

CREDITS: 
Marinara: For her preset. I use her layout as a base, though I believe none of her original prompts remain. 
Celia: The name generation prompt in her preset was the inspiration for the one I am using here, which I modified and expanded to be much more reliable.
Kazuma: Inspiration for the CoT. While the current CoT is entirely my own work, I wouldn't have thought of it if I didn't see it there first. 
Future-Investment303 on Reddit: A post that they put up for random event generation was the inspiration for my own (albeit mine is... again, modified. A lot) 
Did I forget anyone? Let me know :) 

Everything else (mechanics, NPC disposition, etc) is my own work. 

Here's hoping that all the weeks I spent on this gives you a fun roleplay :) 



