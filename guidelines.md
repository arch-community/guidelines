🄯 2025 Anna Kudriavtsev CC BY-SA 4.0

## For new moderators

Feel free to **ask any questions** you have, even if they seem obvious. If you see something you're not sure about, consult with the rest of the team in [#mods], but don't ignore it. <!-- TODO: Erin says this is semantically unclear -->

You are always free to bring up any problems you have with our rules, decisions, or staff team. You will not be punished for speaking out or bringing issues to light. (Don't publicly share private info on users or moderation cases, though.)

If you do not feel comfortable raising these concerns around other staff, you have a few options.
- You can create an admins-only ticket by using `/tickets open` and then using `/tickets adminsonly` in the channel. Admins-only tickets are inaccessible to other mods and sysops, but they're visible to all sudoers. This can be useful to talk about staff team issues, for example.
- You can DM anyone with the sudoers role.
- You can message me, the server owner (Anna, @ap5, 165998239273844736). My DMs are open and I promise I will hear you out.



## Basic principles

When someone first joins a community, **the initial culture and conversations they see act as a powerful example.** If they see high-quality discussion, they will expect it to be the standard and will try to uphold that standard.

Mods should strongly influence conversations toward meaningful, high-quality interactions. Noise, memes, and other "brainrot" should be directed away from discussion channels.

### Our approach

Instead of reactive moderation and focusing on punishments and infractions, **treat people as humans** and ask them to change how they're acting. Expect people to have the maturity to listen to feedback and respond.

The role of the community management team is to manage a community. One way we do this is by filtering out people who do not contribute positively, in favor of those who make others' experience better.

**Don't be afraid to act.** If someone, even a long-time member of the community, is causing issues, don't hesitate to pull them out of the conversation and ask them about it.  People who are resistant to changing the way they interact with the community might not be the best fit to stay in it.

Most conflict is caused by a small set of **recalcitrant, high-conflict people**. Identifying these people early, before they can have a large effect on server culture, is crucial. We've had a few large-scale incidents where this situation was caught too late.

#### ***Note from SSH Addict to new Moderators:***
*“If a rule has been violated but the infraction is minor, address it within the current channel — Anna has already specified this / will specify this (depending on where this wall of text goes) but I'm reiterating.*

*If they (the member or members involved) don't stop, issue a warn or mute them, this depends on the degree to which it is ongoing and is to your own discretion.*

*When muted, talk to the member, don't display aggression or condescendence as that will only make them l*ess inclined to comply.

*If they agree to discontinue or show willingness to change, add a note, unmute them, and see how things go.*

*If they seem unwilling to change or are continuously combative and unrepentant, ban them with the consensus of another mod.*

*In the case that a member has been displaying repetitive/recurring instances of rule-violating behaviour, you may bring them into a ticket or mute them to discuss it — if it is discussed with others, exclusive of them, and a ban or other disciplinary action is concluded to be necessary — then, you should mute them and explain what, why, and how things are going to be done, with context — this is to prevent conflict, confusion, and backlash — whether within the team or from elsewhere.*

*Cases which are deemed exempt from these guidelines — in essence, scenarios that warrant instant bans are when explicit content is involved — text or media — this entails things like pornographic media, gore, racial slurs, bigotry, and a plethora that can usually be inferred from the situation.*

*Another thing I'd like to make clear, disregarding moderation policies — is channel slowmodes — don't set slowmodes higher than an interval wherein conversing is possible. In essence 2 to 15 seconds, 30s or above only during events when @everyone has been mentioned. It may be used briefly to slow chat flow while moderative actions are taken place, but no more than a few minutes as Discord has a tendency to get stuck on slowmode for some users even when changed back. Definitely don't use slowmode in attempt to stop chat flow completely by using an arbitrarily long interval of time — for this reason, we use `%mutechannel` — this doesn't carry any side effects along with it. (unmute with `%unmutechannel`).*

*That's all I can think of for now but I may adjust this later, Thanks and Welcome to the team.”*

### What we don't do

In general, we don't try to punish people. In particular, we don't do temporary mutes or remove privileges as punishments – we mainly issue longer-term temporary bans.

We do not implement a strike system, a point system, or any other kind of progressive punishment system.

Timed mutes and short-term bans are ineffective at resolving conflicts, and only seem to work because they briefly remove the source. Systems like these only multiply the amount of needed moderation work, push people away, and create a culture of fear around moderators.

Staff should not be combative or aggressive toward members, especially not in retaliation.

## Handling disruption and conflicts

If we notice someone causing disruption in the server, use `%op` to designate yourself as a moderator, and talk to them. Bring it up in the chat they're in, or open a ticket. If they seem receptive and stop doing the disruptive thing, that's where it ends, we log the fact that the conversation happened in Valkyrja's logs (using `%addnote`).

If there's a heated conversation happening, we evaluate if it needs moderator intervention. If so, we **find the person at the core of the argument**, mute them, and open a ticket to talk to them, following the same process as before.

If we notice a continued pattern of disruption, we mute them, open a ticket, and ask them about it. Do they recognize what they are doing? Do they seem to be receptive and willing to change their interactions? It's important to emphasize that this is a **conversation**, not a punishment.

If they are receptive, we log a brief summary of the conversation (using `%addnote`) and give them another chance.

If they agree but do not actually change anything, or are combative and ignore the conversation, we explain the situation and issue a **long-term ban** (at least 30 days). 
- If the user is young (approx. 13–18) and it seems like this is due to a lack of maturity or social experience, issue a ban of 1–2 years.
- Do not issue shorter bans, because they don't provide enough time for someone to cool down and reflect on what happened.

The purpose of banning a user is to give them some time away from the server so they can recontextualize things. It is not to hurt or punish someone.

### High-volume conversations

{%hackmd @annaaa/todo %}

mute first, ask questions later
let them work out their emotions in the chill zone
open separate tickets for each user

### Recommended reading

[Rhea Ayase's moderation theory][ayase2017]

From the [Discord Moderator Academy][discordmod]:

- [Handling Difficult Scenarios][discord202]
- [Ban Evasion and Advanced Harassment][discord443]

## Systems and procedures

### Valkyrja

> Bunny Kára is reincarnated Valkyrie Sigrún, leader of nine Valkyries. Kára helps with community management, administration and moderation tasks to help create safe spaces for inclusive communities.
> ― Rhea Ayase, [valkyrja.app][Valkyrja]

We use [Valkyrja] to manage the server. It keeps track of user history, issues and releases timed bans and mutes, keeps logs of activity, blocks spam, and performs some other miscellaneous tasks.

**Never use Discord's UI to perform moderation actions manually.** Always use Valkyrja's commands. This makes sure all actions are tracked and logged. (The only exception is if Valkyrja is unresponsive during a raid or spam-wave.)

### Roles

#### Helpful Users (HUs)

{%hackmd @annaaa/todo %}
recognized for their positive contributions to the community

- levelheaded, maturity etc
- support channel contribution

mod candidate pool
not staff yet
no responsibilities
should not act as mods

HUs have the Delete Messages permission for historical reasons. (If someone is liable to abuse it, they probably shouldn't be an HU.)

mention that we invented HUs

copy in description from old nomination forms

> A good candidate is a member who contributes positively and consistently to the server culture or to the support channels. The group of HUs is also our pool from which moderators are elected. Thus, making a HU makes them a candidate to be elected as mods.

> As many of you know, our users with the Helpful User role are considered our primary backbone of our moderation team. They are both our assistive team as well as the pool from which we draw upon future moderators.

> One of the biggest challenges in a server of over 40K across multiple sub community channels is recognizing quality members that can be turned into Helpful Users. For those new to the server, Helpful Users are the lifeblood of ALC moderation and the first line in the pool in which we draw moderator candidates from. HUs also help to bring things to our attention rapidly. The more we have, the more effective community moderation and moderation recruitment can be.

If you notice that a member is contributing positively and consistently to the server culture or to the support channels, **feel free to give them the Helpful User role** after getting the sign-off of another mod.

#### Mods

{%hackmd @annaaa/todo %}

use old nomination forms + election document as examples

picked from HUs
maintain the state of chat
keep things flowing smoothly
pluck out sources of noise
garden analogy maybe?
18+ requirement due to dealing with NSFW content

#### VC Mods



#### Sysops

{%hackmd @annaaa/todo %}
moderators with more experience – trusted to make judgment calls and deal with larger-scale issues – their only extra permission is the ability to manually issue bans (in case Valkyrja is having downtime).

#### Sudoers

{%hackmd @annaaa/todo %}

logistics, administration, management
steer the direction of things + direct the moderation team
large-scale system overhauls
small team, mutual trust, rarely added
deal with sensitive issues involving personal data
have every permission + can see everything

#### Permission roles

##### Operator

The Operator role is a mechanism to help staff members maintain a separation between participating in the community and acting in an official role. It's inspired by a similar system used on IRC servers.

Use `%op` to distinguish yourself as a moderator. `%op` will give you the Operator role, or take it away if you already have it.

When you have the Operator role, your name becomes bright red, and your profile gets hoisted to the top of the member list. **Being opped is required** to mute and ban.

##### Announcer

Role that allows posting in the aanouncements channel – granted by Anna or an Admin(sudoers), a sysop may grant it if deemed suitable in the absence of Admins – not to be self-assigned (mods) except for during emergencies when announcements or mass pings must be made.


### Notes and warnings

If you give anyone a verbal warning (in chat or DMs, for example), use the Valkyrja command `%addnote` to **log it as a note** for other moderators. (This is an alias for `%addWarning`.)

> [!IMPORTANT]The user will not be notified via DM when you use `%addnote`.
> However, Valkyrja will post the note publicly in [#moderation-log].

If you want to send the user a formal warning, use `%warn`. (This is an alias for `%issueWarning`).

> [!IMPORTANT]The user will receive a DM when you use `%warn`.
> Valkyrja will also post the note publicly in [#moderation-log].

{%hackmd @annaaa/todo %}

(i wrote up a big thing about this a few times - search alc to retrieve it)


Warnings are not meant as a punishment and someone's warning count is not an important number. What's important is whether they are willing to listen to feedback.

### Using tickets

Tickets are temporary, private channels managed by [YAGPDB]. They're most often used for private conversations between specific users and the entire staff team.

Anyone can create a **ticket** using the command `/tickets open <ticket-name>`.

- Tickets are also useful for separating conversations in [#chill-zone] when multiple users are muted.

Tickets are visible to all moderators by default. You can add people to a ticket by using the command `/tickets adduser <user>` inside it. This will let them see and talk in the ticket.

When the conversation is resolved, you can close a ticket with `/tickets close [reason]`. When closed, all messages inside a ticket will be logged in [#ticket-log].

### Muting

Use mutes to pull out users from heated discussions or to talk to them privately. **Do not use mutes as a punishment.**

Valkyrja does not let you mute people without providing a duration. The usual practice is to mute someone for a long time, like `100d` (100 days), and unmute them manually after you're done talking to them. This makes sure that the mute doesn't expire without the situation being resolved first.

When you use the `%mute` command, you should provide a meaningful description, e.g. "final warning about spamming anthropomorphic cow art in #support".

Avoid non-descriptive notes like "talk" or "private chat". The reason you provide will get saved as a note, visible in `%whois`. Writing a meaningful note will help you and other staff regain context on this person in the future. If you forget to do so, leave a note using `%addnote`.

Don't forget to unmute people after you're done talking to them!

#### The chill zone

There is a channel called [#chill-zone]. Staff and muted users can see it and send messages there. Helpful Users can see [#chill-zone], but cannot send messages there.

When Valkyrja mutes someone, it pings them in [#chill-zone] with the following message:
> `{0}`, welcome to the chill zone. This mute is not a punishment. This is a place for private conversations between staff and users. Someone will be here to talk with you shortly.

Muted users can see all channels, but they can _only_ talk in [#chill-zone] and any tickets they're in.

### Banning

In most cases, mods should ask for consensus of **at least one other moderator** before issuing a ban. Ask in [#mods] or [#ticket-discussion]. If there are objections from other staff, have a conversation about it and try to reach a mutual agreement.

Feel free to ban a user **without** waiting for consensus in the following cases:

- Clear spam or blatantly NSFW content
- Overt bigotry, like transphobia, racial slurs, etc.
- Raids and coordinated spam floods
- Preemptively banning bots
- The user has little prior message history
- Judgment calls by sysops and sudoers

### Notes

{%hackmd @annaaa/todo %}
points to still address:
- harassing staff over moderation decisions
- publicly talking about moderation cases

#### Ban evasion

{%hackmd @annaaa/todo %}

not acceptable
alt accounts used for ban evasion are also not acceptable
alt accounts in general are ok, though

#### PluralKit

{%hackmd @annaaa/todo %}

something pluralkit

recent ticket about PK concerns

editing can be used bypass automod
emojis :bell: :question:
system tags
pk;explain

#### Piracy and copyright

The Discord Code of Conduct disallows linking to pirated content. Discussion of piracy is allowed, but in-depth discussion of methods or sourcing content is not.

#### NSFW content

Passing mentions of NSFW topics are allowed, but in-depth NSFW discussion and posting of content falls under rule 1a and should be stopped.

If you're not sure whether something is NSFW, it probably is. For sexual content, refer to the [Discord sexual content policy].

##### Public displays of affection

> the mod team wants to address something that's been causing issues for a while, and hasn't been responsive to moderation.
> 
> there's been a recent trend in conversations, especially in [#lgbtq], pushing against or even blatantly violating **rule 1a** ("NSFW content is not allowed"). our space has members of all ages, many in their young teens, many older adults. this has a high potential of leading to harm.
> 
> interactions like these _cannot happen safely here_:
> - roleplay and extensive flirting
> - teasing, including phrases like "good girl"
> - sexually charged or intimate content
> 
> the mod team will be more closely monitoring conversations to direct them away from these topics.

― [#announcements, 2022][anno2022]

We don't do age verification and we do not allow NSFW content in any channels.

For the purpose of checking whether an interaction could be unsafe, everyone is simultaneously 13 and 65 years old. That is, if it would be creepy for a 65-year-old to say it to a 13-year-old at a local LUG meetup, you probably shouldn't say it here.

This includes stuff like roleplayed kisses and cuddling. It _especially_ includes images or drawings of intimate interactions.

> [!IMPORTANT]
> We cannot control what people do in direct messages or off-platform. However, we can act on reports of interactions that happened off-platform.

#### Channel usage

Make sure to let people know if they use channels incorrectly, including asking for support outside the support category.

#### Ableism

In addition to what's explicitly listed in rule 1, **ableist language** such as the word "retard" and the use of autism as an insult is **not allowed**.

If you do not know whether this applies to a message, ask in [#mods].

#### Paradox of tolerance

Due to the nature of the Arch community, this server tends to attract a certain audience (/g/ users and Luke Smith fans) who we try to avoid by setting a server culture of **mutual respect and [intolerance of intolerance][tolerance]** (also just having pronoun roles available tends to ward them off).

## Server Code of Conduct

### 1. Be respectful

Be nice. Treat others as you want to be treated. Don't troll or deliberately annoy others. Racism, homophobia, transphobia, and offensive language is not allowed.

Follow the [Arch Code of Conduct][archcoc].

This is the most important rule, and the rules below are meant to clarify how rule 1 is applied.

#### 1a. NSFW content is not allowed.

NSFW content is text or media that contains or references suggestive or sexual themes, bodily harm or death, or themes of self harm or abuse. This includes text or media made "ironically" or "as a joke".

#### 1b. Spam is not allowed.

Spam is defined as repeatedly sending the same message or gratuitous self-promotion. Memes, text walls, obnoxious or off-topic gifs, and copypastas should be kept to [#urandom].

#### 1c. Do not ask for privileged roles on the server.

Helpful Users, moderators, and admins are selected from people with a history of helpful, positive contribution; asking to become a moderator is counterproductive.

#### 1d. Follow the support rules.

All support must take place in support channels. See [#support-info] for information and access.

### Other information

- This server is UNOFFICIAL and not sponsored by or affiliated with Arch Linux or its related projects.
- If you have a problem with the server or other members, please bring it up in [#server-meta]. If you do not feel comfortable doing so, feel free to message any online mod.

<!-- Moderation resources -->
[ayase2017]: http://rhea-ayase.eu/articles/2017-04/Moderation-guidelines
[discordmod]: https://discord.com/moderation
[discord202]: https://discord.com/moderation/360060483713-202:-Handling-Difficult-Scenarios
[discord443]: https://discord.com/moderation/360060487093-443:-Ban-Evasion-and-Advanced-Harassment
[tolerance]: https://en.wikipedia.org/wiki/Paradox_of_tolerance

[anno2022]: https://discord.com/channels/399812551963049995/399812823485513728/1052689499370565682

[discordnsfw]: https://discord.com/safety/sexual-content-policy-explainer

<!-- Other references -->
[Valkyrja]: https://valkyrja.app/
[archcoc]: https://coc.archlinux.org/

<!-- ALC channels -->
[#mods]: https://discord.com/channels/399812551963049995/561219694187773965
[#ticket-discussion]: https://discord.com/channels/399812551963049995/1353781170038374480
[#ticket-log]: https://discord.com/channels/399812551963049995/956269591716311110
[#chill-zone]: https://discord.com/channels/399812551963049995/610413272184651786

<!-- dashes for copy-pasting below

U+2012 FIGURE DASH
‒
for ranges in tables

U+2013 EN DASH
–

U+2014 EM DASH
—

U+2015 HORIZONTAL BAR
―
for quotes

U+2212 MINUS SIGN
−
for subtraction or negative numbers

-->