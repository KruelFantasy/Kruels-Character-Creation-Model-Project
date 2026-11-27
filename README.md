# Kruel's Character Creation Model Project

DAT mods for use with XIPivot that change in game character create head models to the actual character creation head models from the creator menu for Final Fantasy 11.

<img width="2326" height="1429" alt="Untitled" src="https://github.com/user-attachments/assets/466d7f67-dc62-4356-9e81-d25a2af8ca13" />

[https://github.com/user-attachments/assets/9453f472-52f3-4eaf-8041-56ba2d47c13d](https://github.com/user-attachments/assets/1cc70394-3d35-4b01-8e78-fb9f21c37d66)

## Summary

The goal is to replace all in game models that use create a character in game heads with the actual heads from the character creation screen.

I plan to fully rig eye and mouth animations on the models, and have already completed the eyes for all of them, and the mouths for some of them.

I have also created from scratch, higher quality inside of the mouth assets to match the high quality of the heads.

I had choices to make as far as in game headgear, I painstakingly adjusted the geometry of all of the heads for every in game headgear and the various "types" flag category they fall into.

Due to some headgear sharing types, it was impossible to have every single piece of head equipment in game work perfectly with every hairstyle on these create character heads.

They look so much better when you have their hairstyles actually rendered correctly when wearing headgear, instead of just hiding it for a lot of headgear like the normal head models used to.

But as mentioned, because some headgears shared flag types, there are a very small amount in the game where I did not want to hide the hair on 1 piece of headgear because of how good it looks, but it also shared the same flag as another piece of headgear that the same hair will clip through.

Again, the amounts of headgear with actual bad clipping in game is extremely small, and usually on headgear you probably won't even come across someone even wearing.

At the moment I have fully completed the base head models for all races and sexes, this accounts for roughly 60%+ of all in game NPC's.

There are a number of NPC's in game that do use the same normal created character heads, but they don't actually use the base DATs for them, and instead use a full skeleton specific mode to that NPC, these and Trusts that also use normal create a character heads will be the final conversion I do, as I have to locate every single one of them and convert them one by one.

I will also be doing custom conversions for some of the more important story NPC's that use variations of the normal create a character heads, for example, I have already done this for Ygnas in his human form and Garazu-Horeizu from the Voracious Resurgence.

<img width="2460" height="1496" alt="Image" src="https://github.com/user-attachments/assets/ddbc824b-033c-4cd6-8158-f1b6c4f5f005" />

<img width="3573" height="1954" alt="Image" src="https://github.com/user-attachments/assets/b3401ea2-a31d-4fd5-990f-49f2aeef90ae" />

<img width="2302" height="1302" alt="Screenshot 2026-11-12 125315" src="https://github.com/user-attachments/assets/fe88ab12-5164-4201-969b-9f2c78a9703d" />

## Optional original created characters

<img width="1981" height="1142" alt="Ulmia Github" src="https://github.com/user-attachments/assets/b0090c82-a4d3-4393-b0a3-22f1fb467650" />

Some prominent characters in game have neither a character creator head, or a good looking higher quality model, Ulmia above is the perfect example of that.
Unlike Prishe, Lion, Nashmiera, Lilisette, etc. Ulmia has a horribly low res model, that is also very generic.
I'm not sure how many of these I am willing to make, as Ulmia took a lot of effort, but they will be optional.
In the example above, I have tried to interpret what I think Ulmia would look like in the character creator model style.

## Current progress

I won't be releasing it till it is basically fully complete, I do not want people to have to constantly be downloading the latest iterations.

Now, this is a massive project, and I'm only one man, so I'll almost certainly miss some things here or there, or possibly want to make some improvements, but this will only be after the full release, I'm not actively
planning to do these things, only if they are needed.

I have been working on this for around 4 weeks so far, it really is a job for a team of people, but I've been burning the candle at both ends to reach some of the bigger milestones before I slow down, the first big
milestone was completing all the base models for all races/sexes, and this is why I have started prepping the Github for it today.

## Performance

It shouldn't really have any effect on in game performance on any PC that isn't a toaster from 1999, as I haven't upscaled or made HD mods of these heads, the screenshots you see are of the pre-existing models from the game files.

I still do not know how big the overall size of the full mod is going to be, as I have not reached the point where I have to locate and count all the random NPC's that use the heads as part of a full skeleton.
Depending on how many of these exist, it could affect the size possibly quite a bit.

I will also want to have a test period in game before I publicly release this, I do not want to be releasing something that ends up causing crashes for people, it will probably be a minimum of 1 week of testing, but i will have friends beta test it also, without beta testing, I wouldn't trust only 1 week.

## Installation
Put the ROM folder into whatever folder you use for your XIPivot mods in:

```
Windower4/addons/XIPivot/data/DATs/…

```
## Release Date

Unfortunately I am not in a place to even give a tentative date at the moment, all I can say is watch this space, and it should be hopefully ready for public release before the end of the month.

## Latest Progress

- Fully built internal mouth geometry and textures for all races, including fanged teeth for Mithra.
- All basic Blinking and mouth opening animations working correctly.
- Mithra ear animations added.
- Tarutaru eyebrow animations added.
- Fixed as many animation issues as I could discover, this was the most difficult and long process, I did the best I can with it, not all are perfect.
- Discovered and fixed all lighting diffusion issues with the new heads.
- Started on the final stage of converting all Trusts and extra NPC's

## To do

- Replace all random NPC's scattered around the game that are using these heads on full skeletons instead of using the head DAT files.
- Replace all Trusts using these types of heads. (same as above, they use full skeletons).

## A personal request

I no longer upload mods to ffxiah.com due to some of the people on the forums there, everyone will know most of the people I am talking about, and the fact that I got a temp block from a moderator for getting abused
by some of them, even though I was the one being cordial.

So please do not link this in any ffxiah.com forums please, and as an added incentive, if this does not show up on the forums by the end of this year, I'll start adding in a lot of my unreleased mods that for the
past 2 years I have only been distributing to friends.
I have been busy this past 2 years as far as FF11 modding goes.
This project is such a big benefit to the whole FF11 community, so it would be far too selfish of me to only give it to friends, so this is my first public release in a long time.
