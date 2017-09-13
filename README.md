# Ethics for Design's subtitles

This repo contains every subtitle available for translation, from the [ethicsfordesign-website](https://github.com/sylvainjule/ethicsfordesign-website) repo.

If you're interested in translating one (or several, or even a small slice) of the subtitles, you'll find the roadmap below. 

If you're not familiar with git, but still want to translate some files, you can google each of these steps which are very basics, and find some nice tutorials in order to get started. Do not hesitate to create an issue, I'll do my best to help you. Otherwise, send us [an email](contact@ethicsfordesign.com) and we'll figure something out. 

1. Fork this repo.
2. Ideally, look for an existing branch for the language you want to edit. If the branch doesn't exists, create one with the name of the language (i.e. `danish`, `german`, etc.)
3. Translate the subtitles content, being very careful not to change any timecode.
4. Once you're done translating (even if the file is uncomplete), create a pull request. We'll check for mistakes, check if our website and font can handle the given language, and then merge it into the website.

##  Syntax

(`xx` being the language code)

### subtitles-xx.srt | chapters-xx.srt

The syntax of the main subtitles is the common one. A subtitle looks like this :

```
13
00:00:43,161 --> 00:00:45,140
I was offered a place and started there
```

You can add italics if needed, with this syntax : `*text-in-italics*`.

### side-text-xx.srt

The syntax here is pretty much the same, except there are two parts, which will create two different paragraphs in the player : the name of the interviewee, and a very short description of his work.

Each is introduced by a prefix (`name::` | `description::`), and are separated by a ` + `).

A side-text subtitle looks like this :

```
12
00:15:56,765 --> 00:16:14,891
name:: James Auger + description:: Designer and associate professor at M-ITI, Madeira
```

The only part you're interested in translating here is the description, for most cases.

You also can add italics with this syntax : `*text-in-italics*`.

**We're looking forward to any contribution !**