# HOYT

_Hoyt_ is a theme built for go hugo with inspiration from [Ben Hoyt's](https://benhoyt.com/) personal website.

![alt text](https://github.com/musale/hoyt/raw/master/public/images/Ben_Hoyt.png "Ben Hoyt's Site")

## Main Features

- Fully responsive including mobile support.
- Excellent code highlight support thanks to Hugo Chroma.
- Display Math with LaTex Math support.
- Google Analytics support.
- Commenting on posts/content with [Utterances](https://utteranc.es/di) or [Disqus](https://disqus.com/).

## ToDos

Feel free to pick up any of these, add more and PR.

- [ ] Social support
- [ ] Multi-language, il8n support.

## Installation

### From GitHub to themes folder

From the root of your static site project

```
$ cd themes
$ git clone https://github.com/musale/hoyt.git hoyt
```

### From GitHub using submodule

```
$ cd themes
$ git submodule add https://github.com/musale/hoyt.git hoyt
```

## Configuration

```
baseURL = "https://gohugo.io/"
title = "Hoyt Theme"
author = "Martin Musale"
copyright = "Copyright © 2019, Martin Musale; all rights reserved."
paginate = 3
languageCode = "en"
DefaultContentLanguage = "en"
enableInlineShortcodes = true
footnoteReturnLinkContents = "^"
theme = "hoyt"
pygmentsCodefences = true
pygmentsCodefencesGuessSyntax = true
pygmentsStyle = "native"
enableEmoji = true
latexDashes = true
googleAnalytics = ""

# Support for [Utterances](https://utteranc.es/)
[params.Utterances]
        repo = "musale/musale.github.io"
        Issue_term="title"
        Theme="github-light"
        Label="github-dark"

[[menu.main]]
	name = "Home"
	url  = "/"
	weight = 10

[[menu.main]]
	name = "Posts"
	url  = "/post"
	weight = 20

[[menu.main]]
	name = "About"
	url  = "/about"
	weight = 80

[params]
	name = "Hoyt Theme"
	tagLine = "all is well"
    description = """
Lorem est tota propiore conpellat pectoribus de pectora summo.

[Redit teque digerit hominumque](https://gohugo.io) toris verebor lumina non cervice subde tollit usus habet Arctonque, furores quas nec ferunt. Quoque montibus nunc caluere tempus inhospita parcite confusaque translucet patri vestro qui optatis ~~lumine cognoscere flos nubis~~! Fronde ipsamque patulos Dryopen deorum.
😉
Exierant elisi ambit vivere dedere
Duce pollice
Eris modo
Spargitque ferrea quos palude
Rursus nulli murmur; hastile inridet ut ab gravi sententia! Nomine potitus silentia flumen, sustinet placuit petis in dilapsa erat sunt. Atria tractus malis.
"""

    avatar = "images/avatar.jpg"
    avatarAlt = "Rihanna"
    avatarTitle = "I love Rihanna"

    [[params.subheading]]
    title = "Mane refeci capiebant unda mulcebat"
    description = """
Victa caducifer, malo vulnere contra dicere aurato, ludit regale, voca! Retorsit colit est profanae esse virescere furit nec; iaculi matertera et visa est, viribus. Divesque creatis, tecta novat collumque vulnus est, parvas. Faces illo pepulere tempus adest. Tendit flamma, ab opes virum sustinet, sidus sequendo urbis.
"""
```
