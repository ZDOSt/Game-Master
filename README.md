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
- Fairly good, almost slop-free writing. This preset targets not a few phrases, but the behaviors that cause crappy writing in the first place. Metaphors, hyperbole, simile, personification, are expressly banned and rarely make their way into a response. Blushing, reddening, eye darkening, flickering and... BS that you can't really see should happen much less often than usual, if at all. Scents/air taste (ozone, anyone? Air tastes like what?) must meet very strict guidelines for it to show up at all. The ENTIRE premise of this preset is: Show what can be PERCEIVED through the senses. 
- NPCs that judge you based on appearance, and how you act or talk. They won't jump into your arms the moment you say something nice, and might even grow to hate you.  
- Your actions, and dialogue can have consequences, and your success is not guaranteed (mechanics). 


