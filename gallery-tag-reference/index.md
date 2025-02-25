---
layout: txt
title: gallery tag reference
css: "a{text-underline-offset:.15em;} /*main*/ a{font-weight:normal; text-decoration-color:#adb9ae;} /*footer a{text-decoration-color:#95a397;}*/ .tag{text-transform:lowercase; font-weight:bold;} aside{font-size:.85em;} main>p:last-child{margin-bottom:0; text-align:center;} h2{font-size:1.5em; margin-top:1.5em;} h2+p{margin-top:.25em;} h3+p,h3+ul{margin-top:0;} h3{font-size:1.25em;} h2 span{text-transform:uppercase;} li{margin:.25em 0;} li>ul{margin-bottom:.5em;} body{background:#dae5d6;} footer{color:#22272b;} footer a:hover,footer a:active,footer a:focus{opacity:.5;}"

tags:
  projects:
    - nm: lineup
      desc: Character height things, which may or may not combine stories.
    - nm: disasterCrew
      desc: The “disaster duo,” two of my oldest human characters, plus other people who spawned when I revisisted their story. Not exactly A Project™ but everyone’s connected anyway; more info <a href='https://a-flyleaf.github.io/toyshelf/disaster-crew'>on my site</a>.
    - nm: TheFirebirdEffect
      desc: Catch-all for a nuzlocke-inspired pokémon comic, active 2016–17. Discontinued; see <a href='https://a-flyleaf.github.io/projects/tfe/'>its site page</a> for the full comic & more info.
    - nm: 404
      desc: An experimental web-based narrative, <a href='https://a-flyleaf.github.io/hello-world/'>launched 2020</a>. No solid plans to do more with it as of 2022.
    - nm: unmooredRandos
      desc: Catch-all for <a href='https://a-flyleaf.github.io/ygbtdm/'><i>You’re gonna be the death of me</i></a> (which didn’t have a name for a few months there, no). Major site art is tagged with <a href='https://www.deviantart.com/a-flyleaf/gallery?q=%23ygbtdm'>the acronym</a>.
  ocs:
    - nm: RPstuff
      desc: RP characters in general; mostly one-offs
    - nm: SladeAuctor
      desc: RP character from 2011; gets his own tag since he was(/is still, sometimes) something of a mascot
    - nm: zero
      desc: former adoptable/closed species from 2012, still gets drawn a fair bit
    - nm: thosetwoguys
      desc: characters originally from <i>TFE</i>
    - nm: sawface
      desc: weird toothy monster (and a vaguely-associated human), first drawn c. 2016
    - nm: cringetober
      desc: fleeting 2020 challenge
    - nm: hellrabbit
      desc: creature that spawned as part of <i>Ygbtdm</i>, but appears on its own sometimes
  gen:
    - nm: bodyHorror
      desc: degree of distortion may vary
    - nm: canidae
      desc: furry frembs
    - nm: creatures
      desc: miscellaneous monsters, Flight Rising dragons (see below) not included
  notmine:
#		#forXYZ, reverse-chronological, then #miscFanart. I can probably re-sort these (and revamp the backend of this page in general but WAVES VAGUELY. NEW VERSION WHENEVER.
    - nm: forXYZ
      desc: gifts, commissions, trades
    - nm: FlightRising
      desc: <a href='https://www1.flightrising.com/'>dragon hell</a>, intermittent since 2015
    - nm: omori
      desc: took over my life c. 2023–24
    - nm: ena
      desc: 2021 hyperfixation
    - nm: StevenUniverse
      desc: space rock obsession c. 2015–16
    - nm: pokemon
      desc: haven’t kept up-to-date in years but it was a good time while it lasted
    - nm: LivestreamEra
      desc: ah, 2011–13 “crack”
    - nm: miscFanart
      desc: anything not covered elsewhere
  comp:
    - nm: notedump
      desc: visual guide-type things
    - nm: sketchdump
      desc: buncha doodles on the same canvas, either drawn as such or a non-roundup compilation
    - nm: roundup
      desc: monthly doodle dumps of things I didn’t think warranted standalone posting, including process sketches
    - nm: summary
      desc: (mostly-)yearly art summaries that put things together all nice and tidy
  type:
    - nm: 3d
      desc: <a href='https://www.blender.org/'>Blender</a> is a wonderful program
    - nm: animation
      desc: either gifs or description-linked videos
    - nm: comic
      desc: entirety of <i>TFE</i> not included
    - nm: edit
      desc: more photoshopped (without Photoshop™) than drawn
    - nm: MSPaint
      desc: exactly what it says on the tag
    - nm: screenshot
      desc: attempts to imitate or actual usage thereof
    - nm: template
      desc: memes (in the old-dA sense of the term) & old lineart/base usage
    - nm: video
      desc: animations & timelapses
    - nm: website
      desc: featured on and/or drawn primarily for my website somewhere
    - nm: writing
      desc: old and crusty
  style:
    - nm: BW
      desc: intentionally two-tone, usually black-and-white
    - nm: lineless
      desc: flat/not painted
    - nm: neon
      desc: eyeburners!
    - nm: painterly
      desc: blending galore
    - nm: pixelArt
      desc: tiny dots
    - nm: scribbly
      desc: love me some loose lines
  misc:
    - nm: forxyz
      desc: has already been listed above but why not
    - nm: icon
      desc: art that I used as my dA icon at some point, although I forgot what the very first one was….
    - nm: redraw
      desc: revisiting my own stuff; both old and new versions get this tag
    - nm: tumblrLink
      desc: because a lot of these links are broken and at some point I need to figure out what to do with them
    - nm: website
      desc: also listed before, idek; sometimes these deviations are essentially a webpage ad
---
Because [my gallery](https://www.deviantart.com/a-flyleaf/gallery) is sorted almost exclusively in reverse-chronological order, I use tags to actually categorize things. Lots and lots of tags <span style="display:inline-block;">\o/</span>

<aside>(As for why I'm using an offsite page instead of, say, a journal entry? Editing it (and tracking all the changes) was a hassle :V The magic of coding is that I can make stuff like this a billion times easier.)</aside>

If the descriptions seem unnecessarily detailed, it's because I confuse myself on what goes where a lot. This is a guide for me as much as anyone else <span style="display:inline-block;">:P</span>

<section id="subject" markdown="1">
## by <span>subject</span>
Some people and other critters that show up a lot, original and otherwise.

### recurring characters
<ul><li>main casts<ul>{%for tag in page.tags.projects%}<li><b>#<a href="https://www.deviantart.com/a-flyleaf/gallery?q=%23{{tag.nm|downcase}}" class="tag">{{tag.nm}}</a></b>{%if tag.desc%}: {{tag.desc}}{%endif%}</li>{%endfor%}</ul></li>
<li>other characters (see also: <a href="https://a-flyleaf.github.io/toyshelf/misc/">Toyhou.se knockoff site</a>)<ul>{%for tag in page.tags.ocs%}<li><b>#<a href="https://www.deviantart.com/a-flyleaf/gallery?q=%23{{tag.nm|downcase}}" class="tag">{{tag.nm}}</a></b>{%if tag.desc%}: {{tag.desc}}{%endif%}</li>{%endfor%}</ul></li></ul>

### everything else
<ul><li>general subjects that come up a lot<ul>{%for tag in page.tags.gen%}<li><b>#<a href="https://www.deviantart.com/a-flyleaf/gallery?q=%23{{tag.nm|downcase}}" class="tag">{{tag.nm}}</a></b>{%if tag.desc%}{%if tag.desc%}: {{tag.desc}}{%endif%}{%endif%}</li>{%endfor%}</ul></li>
<li>subjects of things by other people<ul>{%for tag in page.tags.notmine%}<li><b>#<a href="https://www.deviantart.com/a-flyleaf/gallery?q=%23{{tag.nm|downcase}}" class="tag">{{tag.nm}}</a></b>{%if tag.desc%}{%if tag.desc%}: {{tag.desc}}{%endif%}{%endif%}</li>{%endfor%}</ul></li></ul>

### giant canvas collages
Compilations of some sort. Some things got uploaded achronologically, which makes the tag order weird; see [the sub-gallery](https://www.deviantart.com/a-flyleaf/gallery/81345929/compilation-stuff) for everything arranged proper.

<ul>{%for tag in page.tags.comp%}<li><b>#<a href="https://www.deviantart.com/a-flyleaf/gallery?q=%23{{tag.nm|downcase}}" class="tag">{{tag.nm}}</a></b>{%if tag.desc%}: {{tag.desc}}{%endif%}</li>{%endfor%}</ul>

Art *in* sketchdumps/roundups/summaries may or may not be tagged for individually (i.e.&nbsp;Zero appears in one little doodle in a roundup; whether the roundup is tagged #zero depends entirely on my memory at the time), I am not consistent with it. Maybe someday ¯\\\_(ツ)_/¯
</section>

----

Tags henceforth are ordered alphabetically.

## by <span>type/medium</span>
Assume static 2D digital drawings unless otherwise noted.
<ul>{%for tag in page.tags.type%}<li><b>#<a href="https://www.deviantart.com/a-flyleaf/gallery?q=%23{{tag.nm|downcase}}" class="tag">{{tag.nm}}</a></b>{%if tag.desc%}{%if tag.desc%}: {{tag.desc}}{%endif%}{%endif%}</li>{%endfor%}</ul>

## by <span>style</span>
Because I don't have a default---although currently, sketchy things and anything with normal lineart goes untagged.
<ul>{%for tag in page.tags.style%}<li><b>#<a href="https://www.deviantart.com/a-flyleaf/gallery?q=%23{{tag.nm|downcase}}" class="tag">{{tag.nm}}</a></b>{%if tag.desc%}{%if tag.desc%}: {{tag.desc}}{%endif%}{%endif%}</li>{%endfor%}</ul>

## miscellaneous categorization
Things I'm not sure where/how else to categorize.

<ul>{%for tag in page.tags.misc%}<li><b>#<a href="https://www.deviantart.com/a-flyleaf/gallery?q=%23{{tag.nm|downcase}}" class="tag">{{tag.nm}}</a></b>{%if tag.desc%}{%if tag.desc%}: {{tag.desc}}{%endif%}{%endif%}</li>{%endfor%}</ul>

There's also <a href="https://www.deviantart.com/a-flyleaf/gallery?q=%23untagged">the <b>#untagged</b> tag</a>, for stuff that I don't know how to tag yet.

----

*A'ight enough of that*. Head [back to the gallery](https://www.deviantart.com/a-flyleaf/gallery/all)~