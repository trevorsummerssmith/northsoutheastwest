_`ALL OF THIS COPYRIGHT 2016 TREVOR SUMMERS SMITH.`_
***
# _North South East West_
***
# 1. Nature of the Beast
_In which the game is described._

I’ve felt for a long time that a key to empathy is seeing another’s history. We see another person and look at their current state. We see: person in my way in the subway line, person who has something I want, addict, rapist, murder, thief. Yet, profoundly and so simply, when we see another person’s history we have empathy. We see a defenseless child being beaten, the neurotic coworker growing up in a home that required hyper vigalence, and the rapist being raped. This simple shift from current state, to directed acyclic graph of states.

North South East West (hereafter _NSEW_) is about exploring a world of people and developing your own character’s history within that world. You will choose your character’s actions, and thereby your character’s persona in the world. Will your character be kind, loving? Do you come to other’s aid when they are in need? Do you build an empire and become successful in material things? Will you rob and murder for gain?

NSEW’s game engine has two foundational properties:

1. the locus of activity is not _player_ driven
2. the story of the game is generated dynamically

In many games the locus of the _game engine’s attention_ is focused on the player’s character. For example, in many first person shooter games, the enemies do not need to exist until the character can sense them. Furthermore, the enemies only need to exist to be _something (for the player) to shoot at / something (for the player) to avoid being shot by_.

NSEW is more akin to a simulation: the world’s complex characters exist without the player’s character’s interactions. The world’s characters have goals, hopes, dreams, respond to their environment and have emotions. The player’s character has no special significance to the rest of the characters in the simulation, nor the simulation itself. While there is clearly significance to the player’s character and the player — the player’s character is the only one the player controls.

In NSEW there are no pre-created stories. Instead, each character has its own mind that captures the characters ability to reason about its environment and world, and take actions towards the goals it wishes to work towards. As characters interact with their environment (and other characters) they will change, and be changed. This reciprocal interaction creates a dynamic system which allows for interesting, emotionally engaging characters to emerge.

NSEW allows for both exploratory play and goal directed play. For example:
 - You come across a baker in a village whose bread was recently stolen. She asks you to help her find the person who stole the bread.
 - You comfort a grieving father who recently lost his daughter.
 - You enter a village you have never been before. You spend time talking with the people in the village. Learning about them and their lives.
 - You aid a group of villagers in creating more farm-able land so that they will have more food.

As you move your character through this world (and your character’s life across time) you create your character’s kamma. This influences how other characters interact with you and, reciprocally, you them.

## Characters
>**Emotionally engaging, interesting, dynamic characters are the essential building block for this game.**

What makes a character emotionally engaging? What makes a character dynamic? What makes a character interesting?

Let’s define:
- **dynamic** characters respond to the environment
- **interesting** the player is not easily able to “get a feel” for how the system works
- **emotionally engaging** the player _empathizes_ with the other characters

We want a game in which the characters respond to the environment in ways that are not straightforwardly predictable, and produce emotionally engaging stories. The stories of the character’s lives should be the stuff our lives are about, that make our lives engaging: birth, life, death. Desire for achievement, love, loss, struggle and how we deal with the continual, inevitable suffering that is inherent to this life.

### Character Stories

Some example stories to give a flavor of the type of characters and interactions NSEW should create.

#### Josephine
 
>Josephine is an older woman. Her children are grown and still live in the town. She does basic food preparation work at this point in her life. The town experiences a severe draught. The lack of food puts strain on everyone in the village. Reports of theft and violence begin to spread, as the villagers are going hungry. Josephine considers the situation and calls a town meeting with the village she cares so much for. Josephine explains how the town needs to become brothers and sisters in their suffering. That by helping one another they will be better off. She becomes a de-facto leader during this time of strife. The people listen to her and the violence goes down. The draught worsens and people get more hungry. Eventually, Josephine proposes that the town explore moving itself North, where there is no draught. The town decides to do this and moves itself to another chapter.

#### Micah

>Micah is a young man still living with his parents. A fire burns his parent’s house down. Both of this parents are killed. Micah does not know how to express the tremendous grief he feels. He isolates himself from his fellows and his anger grows at the loss of his parents, and the unfairness that his parents were killed. He continues to isolate and looses his internal sense of connection to the rest of his village. Eventually, Micah leaves his village to escape the memories of his parents. While traveling Micah meets with a band of Thugs. He joins these murderous thieves as he finds a place where he can continually disassociate from his emotions, and express his anger through acts of violence.

#### Kenan

>Kenan is a middle aged man. He is a farmer in a village. He is anxious all of the time due to a combination of how he was raised, and his genetic makeup. Kenan’s anxiousness creates a “short-temper”. He does not have many friends. People quickly learn to stay away from Kenan. One day, Kenan learns of meditation. He realizes that he feels anxious all the time. He takes this wisdom (that he feels anxious a lot) and uses this to motivate himself to try to use meditation. Slowly, over time, Kenan gains flexibility over his responses to others. He looses his temper less. In addition, he begins to feel less anxious. Even when he is anxious he learns to respond in a way that feels good for him. Kenan begins making friends in the village. Over time, he meets another man and falls in love. They move in together and become partners.

#### Zaya

> Zaya is a young woman just out of her village’s school. She wants to become a cook. Her father has always been very demanding — requiring perfection from her in whatever task she does. Zaya becomes an apprentice cook at her village’s restaurant. She is overjoyed. After working at the restaurant a short while some food goes missing. The restaurant owner blames Zaya as she recently joined. Zaya did not take the food but is filled with shame as she is fired from her job. Her father disowns her from the shame he feels is brought upon their family. Zaya leaves her family village — the only village she has ever known. She travels to another town and gets work as a cook. She is very insecure now and is filled with a sense of shame. Without any friends or help, she begins abusing alcohol and soon becomes an addict.

## Graphics
The game will have 2d graphics with the player able to move around the 2d grid of the world. Think Super Nintendo’s Zelda and Final Fantasy III. However I want the graphics to bleed a lot and not actually look too similar to either of those games. The end product I think will look more like water colors. [Future Unfolding](http://futureunfolding.com) has amazing graphics and isn’t what I want, but does give an example of a game with “bleeding” colors.
 
# 2. Design
_In which the game mechanics are described in as non-technical, non-implementation-specific way as possible._ 
 
## Characters

Before we begin discussing emotions, which I think is one of the harder parts of this, let’s discuss “what a character _is_” without their emotions (if that is possible).

### Character Needs
Each character will have a set of needs. The Buddha said that people physically need food, shelter, clothing, and medicine (the four requisites). In addition to those four, we also have:
- physical safety (related to shelter/clothing)
- emotional regulation/socialization
- well-being for other characters
- sexuality (this needs some more thought)

We can think about well-being for other characters as a hierarchy of in-groups. First it starts with the character themselves, then family/romantic partners, village, state, and finally all of humanity.

### Character Goals
A character will have a set of short term and long term goals that they will take actions to work towards. The character wants to maximize their needs, and will choose the goals that maximize their needs. Examples of long term planning are “build a grain silo so as to increase food for winter; build a house so as to increase health by by limiting exposure”. Examples of short term planning goals are “kill this deer right now to get food; gather a plant to get food; attack this person who is dangerous so I can preserve my physical safety”.

With a set of goals, the character will now take actions to meet their goals.

### Character Memory

The memory model is heavily based upon the interpersonal neurobiology work of David Siegel[^1]. Briefly, in this model, human beings have two kinds of memory: _implicit_ and _explicit_. Explicit memory is the kind of memory where one feels that they are “remembering”. Explicit memory includes two subtypes: 1) semantic (facts) 2) autobiographical (felt sense of self existing at another time). Implicit memory does _not_ have the sense of remembering associated with it. Implicit memory has to do with the “mental models” or categories that are constantly in use to understand our world. For example, when we see a tiger and think “fear” or we see a candy bar and feel hungry. These are categories that identify at a fundamental level what we’re looking at without the idea of “remembering” having interacted with candy bars in the past.

That probability that an explicit memory is stored is described by a normal distribution[^need to double check this] of the current emotional intensity. _Emotionally non-interesting things, and traumatic things are not stored_. In addition, explicit memory requires focal attention to stored[^It is hypothesized one of the reasons traumatic things are not remembered is because attention is intentionally diverted during the experience]. On the other hand, implicit memory does not require focal attention to store — implicit memory is (basically) always storing. In fact, due to ways that the brain re-processes stressful events, implicit memory stores traumatic things very well. The difference in how explicit and implicit memory store memories seems to be critical to how human beings are. An example to illustrate:
> a child is brutally attacked by someone wearing a red shirt. The child’s explicit autobiographical memory does not store a memory of the event, due to its traumatic nature. The child’s implicit memory creates a memory, which links the emotional state the child was feeling at the time with the other sensory input the child experienced. Namely, the child’s fear and anger are linked to the color red, and specifically a red shirt. The child, now an adult, will feel anger and fear whenever they encounter a person wearing a red shirt. They will have no explicit reason as to why this is. Instead, they will experience “randomly” (and perhaps frequently) feeling anger and fear. They will likely self identify as an angry and frightened person. Because these type of emotions can be difficult to deal with, these states, if not directly addressed, can become a defining personality feature of the individual. IE that person can be a fearful and angry person.

It seems to me this is a key component of how human beings develop, and differentiate. I would like to use this same distinction for the character’s brains.

Let’s go with the following for memory storage:

**Implicit Memory Storage** will be represented as a graph. The vertices of the graph will be **mental objects** `TODO define what that is` and the edges will be an integer strength. As new experiences happen, the strength of edges will be increased that happen in the same experience. Note that this is equally true of mental objects that are worldly things, as well as mental modes of operating. For example, edges will be added between the fight/flight/freeze mental mode and the worldly things that are going on when that mental mode is engaged. There will be other processes that decay the edge weights over time. `TODO priming`

**Explicit Memory Storage** there are two kinds: the factual store that allows the character to _know_ things. For example, there is a village 5 miles from my current location, this person I am talking to is named Jane and has a house down the street. The factual store is atemporal and is just data. **Factual store retrieval** is interesting because we probably want something like a semantic web kind of thing where we search both on current links between objects, and different types of meta data that these objects contain. **Autobiographical memory** is important for creating a sense of coherency in the character’s life. Without a sense of the autobiographical events, the characters are not able to make sense and progress through the inevitable difficulties that befall them. **Autobiographical memory storage** can be thought of a separate type of links on the same graph as the factual store. The autobiographical (also called **episodic**) memory store will store memories based upon focus, interest and emotional intensity. When a memory is stored, we can think of a new vertex being created that includes relevant information about this episode. For example, where the character was located, relevant information about themselves at that time, how they felt, how old they were. 

`TODO thoughts on the retrieval process and re-storing.`

### Executive Functions, Flight, Fight & Freeze
There are different cognitive systems available to each character. Each system has a different level of **response flexibility** and **group of people it cares about**. We’ll talk in the next section about stimuli (both internal and external) and how/why these different systems are engaged.

The highest functioning level allows the character to think for a long time about their decisions and the ramifications of those decisions, even if they are experiencing intense emotions. In addition, the highest functioning level allows that character to access, and optimize for, the largest **in-group** that the character can engage with. `TODO need more on in-groups.`

The fight/flight/freeze system only cares about the individual’s needs, and no other group’s needs. These systems do not allow the user to think through their actions. In humans, it is thought that the use of non-myelinated neurons are used[^3] during the fight/flight/freeze response so the speed of synapse firing is a few order of magnitude slower than usual. Literally, one’s thinking is slow during these times.

During the freeze dissociation mode, understanding of emotions (both the character’s own emotions, and the emotions of other) is not possible. Fight and Flight can still have a very basic understanding of emotions but there is basically no response flexibility — if an emotion is perceived as hostile it will instantly be acted upon (without checking if there is actually hostility present).

### Stimuli Processing (& Emotions)

The characters have three senses:

1. Sight
2. Hearing
3. Interception

Interception in this context will mean bodily sensations connected to emotions. For example, when humans get nervous, their stomachs will tighten; when angry a warm feeling; and when sad a hollow energy in the throat. The character also has the internal senses of hunger, thirst and feeling physical pain, but these will not be dealt with in these same channels as we’re describing here `TODO reference sections`.

Sense stimuli are processed as follows[^initial orientation, elaborate appraisals and arousal are all IPNP terms]:

1. **initial orientation** the first stage that looks at the stimulus. Very quick. Sends a message to the body that is _pay attention_ or not.
2. **elaborative appraisals** more sophisticated systems that mark the stimulus as _good_ or _bad_ that is _approach/withdraw_.
3. **arousal** the two previous steps are about internal changes, this state is the action taken by the character based upon the appraisals.

The appraisals can create an overall state of a **categorical emotion**. For example, if a sound is heard at someone’s door they might be expecting their partner coming home. The perception created could be one of “my partner is coming home”. At another time, if one is in a war, that same sound could create “imminent danger” and ready the body for attack. These two **perceptions** could be created from the same **raw sense stimuli** — the sound.

One idea of meditation is that it gives one access and awareness of the **raw sense** and **perception** streams as two streams. One can think of the raw sense stream as bottom-up, and the perception stream as top-down.

_This section is inspired by 1) the Buddha’s description of the six sense bases, Āyatana[^4] and 2) The Developing Mind[^1]._

_See the sense base footnote for original source. [Wikipedia](https://en.wikipedia.org/wiki/Ayatana) gives a good overview. I was surprised to see that The Developing Mind offered a complimentary, if not exactly the same, view._

### Emotions
Let’s call the “emotion” words we are familiar with “categorical emotions”. For example sadness, anger, fear, surprise and joy[^2]. Basically, we’re not interested in categorical emotions. We’re instead interested in how a given “state of mind” represents itself w/r/t decision making and action.

Let’s define these though, in terms of the categorical emotions:
- sadness - character will have less awareness of other’s emotions. 
- anger - less aware of other’s emotions. More prone to taking violent actions. _fight/flight/freeze_ system.
- fear - same as anger
- surprise
- joy

`TODO — different emotions have access to different memory types. For example, depressed people only remember their sad memories. Think — when I am sad I feel like I’m going to be SAD forever.`

### Constraints
How do we create a drug addict?

## Emotion Expression & Language
As stated previously
> emotionally engaging, interesting, dynamic characters are the essential building block for this game

How do understand another’s internal state? With human beings there are two ways: 1) non-verbal and 2) verbal. Non-verbal facial cues are especially important for conveying emotional state. Large portions of the human brain are devoted to understanding another’s facial expressions. There are other non-verbal cues such as overall body posture (leaning in, standing away, aggressive). For the game I want to have something that feels very emotionally engaging to take place of facial expressions. I think that facial expression might be too difficult to pull off effectively. This might not be the case and I will spend some time investigating. However, I am thinking something more like the character avatars will have an aura around them. This aura will vary in color and area. These will correlate to the emotional valence and intensity the character is feeling. Will nee to explore this to see if it feels right. I think that there is a rich set of information in the world of animators. Will talk to Rami (animator friend) about expression emotions using colors and intensity.

The second way of expression is verbal. This seems especially difficult. Natural language (written and oral) shows us fluency, class, culture and other nuances of the author. Readers of their native language are especially sensitive in even minor deviations. Initial ideas about the language question were to generate a small, restricted subset of English. However, given the above points I think that this will not be _emotionally engaging_.

Eric Morley made a great point about humans’ interaction with graphics as opposed to language: _“no one watches the Simpsons and says ‘Homer is yellow’ this is really not realistic.”_ This feels right to me in my experience. One sees this all over with cartoons — inanimate and anthropomorphic creates are frequently given human features only via a few minor physical changes (eg add mouth and eyes to a potato) — and these cartoons instantly feel emotionally compelling. I want to go with this. Let’s say there’s a working hypothesis that if we engage the more-left-brain-language processing _via_ the more contextual, right brain, image processing mechanism, the language will _not_ feel weird.

The plan will be to create this simplistic subset of English (as originally thought) but instead map this to a emoji-like language.

## Other

### Race, Gender, Sexuality
The game will have race, gender and sexuality. These are core reasons for why strife happens in life. Not sure yet how these will all manifest.

# 3. Technical
_In which the game mechanics are described in way that (hopefully) facilitates implementing them._

## Planning

Uncertainty seems to be important w/r/t this problem. Things that are certain for a character:
- Set of actions the character can take, and how those actions (immediately) affect the world. EG build grain silo => increased ability to store grain, eat food => less hungry.
- Set of actions other characters can take, and how those actions affect the world.

Things are uncertain for a character:
- How other characters will act
- What is happening in parts of the world the character cannot see/hear.

So, it seems to me we have two separate problems:

 1. Decide upon a set of goals that maximize the properties.
 2. Decide upon an action this turn that works towards achieving the current goal set.

Let’s discuss some different concrete worlds, and emergent behavior one would like to see.

Terms:
* **resource** food, wood or medicine plants. These are all distributed across the board so that there will be higher concentrations in some areas.
* **possession** a resource a character has gathered.
* **medicine** will cure a disease. There will be one disease in the game that character’s can die from. Initially, the disease will occur via spontaneous generation. When a character gets a disease they will know that they have X amount of time to find medicine until they die.

**Gather World**
Needs:
1. food
2. shelter from exposure (physical health)
3. medicine

Actions:
1. move
2. gather: food, wood (create shelter), medicine
3. build shelter (requires wood)
4. take medicine (requires medicine)
5. eat food (requires food)

Information/Memory:
Characters can see the entire world. They have perfect memory.

**Gather w/not full information World**
This is exactly the _Gather World_, except the characters cannot see the entire world.

Information/Memory: Characters cannot see the entire world. They have perfect memory.

Behavior we’d like to see:
* **Prioritizing exploration**
	* Characters are hungry, not see any food and decide to explore new areas. We’d want the ‘simple’ players in this model to perform well, so probably minimizing their regret[^Seems this has relevant information on this idea https://en.wikipedia.org/wiki/Multi-armed_bandit].
	* Character is not hungry but has not explored a nearby area. At some point the character should decide to explore the area, even though they have access to food.
	* I’ld like the “desire to explore” be a parameter that can be changed per-character. Some characters would not want to sit still, others would never want to explore.

**Gather w/Basic Communication World** 
Needs: same as _gather world_
Actions: same as _gather world_ plus
1. Share Information: requires two characters to be located in the same location. Character A knows about geographic information and can share that with Character B. An example is “food located  at x,y”.

Information/Memory: same as _Gather w/not full information World_.

Behavior we’d like to see:
* Character use information from a communication to plan.

**Gather w/Trade World** 
Needs: same as _gather world_
Actions: same as _gather world_ plus
1. trade - requires two characters to be located on the same place. Trade can swap two possessions. Need to flesh out exactly how the trade will work but the spirit is that a character will want to trade if they need something and it is cheaper to trade it than for them to work to acquire it. I imagine there will need to be a weighting for past-labor vs present needs. For example, a player might trade a lot of wood for medicine if the player knew they were going to die soon.

Information/Memory: same as _Gather w/not full information World_

Behavior we’d like to see:
* _Geographic specialization_: we would like to see that a character would return to a medicine place to harvest medicine and then trade it at a good trade price.

**Care about select others World**
Needs: same as _gather world_ plus
1. needs of a set group of other characters. These needs are the same as this character, except for the others. We’ll call the others _family_.

Actions: same as _gather world_ plus
1. give - like trade but one side swaps nothing.

Behavior we’d like to see:
* Character gets medicine for a sick family member when the character is not sick.

* _Communicate about a learned trade route_ a character who has learned that a trade route is profitable at the moment could share this information with another character. (Thought: this could basically be the location information with a DAG of actions that produces a result).

# Roadmap
_In which plans are discussed._

1. **Basic planning: one utility curve** create a character who has one utility curve (food) and move, eat food actions. The character does not have theory of mind for other characters.
2. **Basic planning with theory of mind** character has the same actions as in previous. Their goal is the same. However, they know will try to outsmart the other characters.
3. **Planning with more actions and utility curves** let’s add more utility curves and more actions and see how things work.
4. **Caring about others** create a character who wants everyone to do the best, who wants themselves and a few others to do the best, etc.

`TODO how does meditation factor into this. Do we want the characters to be able to learn a couple specific things in the game? Seems like learning specific actions and their outcomes is a much more constrained problem. IE not learning the action and its outcome, nor learning action from outcome.`

***
_`ALL OF THIS COPYRIGHT 2016 TREVOR SUMMERS SMITH.`_
_`TREVORSUMMERSSMITH AT GMAIL.COM`_

[^1]: The Developing Mind by Daniel Siegel
[^2]: These are the “cross-cultural” emotions. Apparently there is a lot of dispute as to what an emotion is and if these “cross-cultural” emotions are things. Discussed in[^1].
[^3]: This is basically Porge’s Polyvagal Theory.
[^4]: Majjhima Nikāya 148 _Chachakka Sutta_ The Six Sets of Six. Translated by Bikkhu Ñānamoli and Bikkhu Bodhi.