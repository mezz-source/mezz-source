# good morning/night/day
I honestly couldn't tell which it is, but I'm sure you can figure it out yourself

```lua
-- TODO: why are we saying this? who event put this here?
-- TODO (reply): shutup
```
### whoami
I'm mostly a game developer for Roblox, but I have future sights on becoming and elusive *backend developer⭐* (still learning fundementals). I do way more than just cracking away at Luau & Python though! I'm a creative writer, a composer, technically a voice actor now, an animator, and a game designer! Obviously I'm not a master at all of these things, but I shoot my best shot 🫡

While it sounds cool, backend development actually just *"how do I not explode because of past mistakes"* as a discipline. Honestly, game development isn't far off in terms of architectural *"please don't screw me up later"* except it's bugs are 500% more visible to anybody touching it, but it's more fun to engage with

You may be asking; **why this when you can do the much easier frontend or literally anything else that doesn't risk exploding user data?** Simple, I am terrible at art design! And I do **NOT** like fine tuning UI so that it fits bleed margins or aspect ratios. I've never enjoyed designing CSS or HTML, it's just not as fun as being the data wizard. Besides, it's not a question of if you'll explode, it's when!

This is a part of the fickle fantasy that all CS majors have; If I can code, somebody will want me! It's a noble pursuit but one that often ends with fifty compilation errors because a package somewhere is having a heart attack and you don't know where, and ninety applications that end up in the void

```python
# NOTE: Do not call this function without the user_id. It says it's optional; it isnt!
```

### education
Graduating from a technical high school in Texas, been in computer science for four straight years. Loved every second that wasn't me staring at algorithms for computer science exams:
1) AP Computer Science A
2) AP Computer Science Principles
3) PCEP Python Certified (at least... for beginners)
Never minded taking classes, but projects are the real bread and butter

```lua
-- FIXME: Fix users accidentally being deleted from production when applying modification to their bio
```

Most of my learning comes from my own time learning backend principles. I remember wasting periods at a time just staring at different authentication methods or what a gRPC is and how could I eat it. In fact, I've been looking into containerization and deployment spaces as my next topic of learning! 
### current brain dump
### notes app
An app that allows users to sign up, post a note, and get banned for movie spoilers. Made with our beloved new cool kid FastAPI. Has a really basic ACAB role system and some very basic SQL w/ sqlalchemy as the database

Also has some real nice pydantic & msgspec usage to optimize requests and business logic to be nice and speedy.

Repo link: https://github.com/mezz-source/full-notes-app

Also plays gunshot noises via websocket whenever somebody gets banned. Nice.

### damage system
Used to work on a Roblox game that used a particularly ancient weapon base. It was my job to patch it and have it comply with a buch of outdated NPC code's own damage modules. Used some cool *damage context* code pipeline

```lua
local damageContext = {
	amount = 32,
	damageType = "Blunt",
	attacker = Entities[currentCharacterModel],
	victim = Entites[currentTargetModel],
	canAct = false
}
```
Said context was generated on the fly during business logic, or sent directory
```lua
DamageService = require(ServerScriptService.DamageSystem)
DamageService:SendDamageContext(damageContext)
DamageService:SendDamage(32, 'Blunt', currentCharacter, currentTarget, false)
```

Most of the magic of this project was in the business logic which understood how to apply damage to different targets, and signal dispatching to other scripts when a target was killed of a specific type

```lua
killEvent:Fire(killedTarget, attacker, deathType)
```

Wish I could show but it is in fact not a repository and I cooked it right in Roblox Studio itself
### python file that plays emote music
Roblox has emotes; why don't we have music for it to?!

File link: (i will drag them from my tower later)

```python
# NOTE: it's literally one python file but i might expand it
```

maybe when i get home today


```lua
-- TODO: ensure this portfolio is allgined with HTCPCP protocols. also add a meaningful ending which also acts a critique to post modern capitalistic ideas
```
