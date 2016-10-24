# Awesome Interactive Fiction

A curated list of interactive fiction frameworks, tools, and resources.

-   [Overviews](#overviews)

-   [Software](#software)

    -   [IF Developement Tools](#if-developement-tools)

    -   [Interpreters](#interpreters)

        -   [Cross Platform](#cross-platform)

        -   [Mac OS](#mac-os)

        -   [MS Windows](#ms-windows)

        -   [Mobile Devices](#mobile-devices)

        -   [In-Browser Players](#in-browser-players)

    -   [Mapping Tools](#mappping-tools)

-   [Collections](#collections)

-   [Blogs](#blogs)

-   [Competitions](#competitions)

-   [History](#history)

    -   [Books](#books)

    -   [Documentaries](#documentaries)

-   [Tutorials](#tutorials)

-   [Conferences](#conferences)

## Overviews

-   [Emily Short's Introduction to Interactive Fiction](http://inform7.com/learn/eg/dm/IntroductionToIF.pdf)

-   [Zarf's Interactive Fiction](http://eblong.com/zarf/if.html)

## Software

### IF Developement Tools

-   [ADRIFT](http://www.adrift.co/) (Adventure Development & Runner Interactive Fiction Toolkit)

-   [Alan](http://www.alanif.se/)

-   [Curveship](http://curveship.com/)

-   [Hugo](http://www.generalcoffee.com/)

-   [Inform 6](http://inform-fiction.org/)

-   [Inform 7](http://inform7.com/) — based on natural language.

-   [Ink](https://github.com/inkle/ink)

-   [TADS (Text Adventure Development System)](http://www.tads.org/)

-   [Tuvi](https://github.com/jaywengrow/tuvi)

-   [Twine](http://twinery.org/)

-   [Undum](http://undum.com/)

-   [Varytale](http://varytale.com/books/)

-   [Versu](http://versu.com/)

### Interpreters

#### Cross Platform

-   [Fizmo](https://fizmo.spellbreaker.org/) — a generic Z-Machine interpreter-development library in plain C, used in various interpreters. Supports Z-code (1-5, 7 and 8).

-   [Frotz](http://frotz.sourceforge.net/) — for Linux & Mac OS X, supports Z-Machine story files.

-   [Gargoyle](http://ccxvii.net/gargoyle/) — for MS Windows, Linux & Mac OS X; supports most story file formats by including the following interpreters: Agility, Alan 2 and 3, Frotz (glk port), Glulxe, Hugo, Level 9, Magnetic, Scare, Tads 2/3.

#### Mac OS

-   [Spatterlight](http://ccxvii.net/spatterlight/) — story files supported: AGT, Adrift, AdvSys, Alan, Glulx, Hugo, Level 9, Magnetic Scrolls, TADS (text-only), Quill, and Z-code (except v6).

-   [Zoom](http://www.logicalshift.co.uk/unix/zoom/) — supports Z-code, TADS 2/3 and HUGO story files.

#### MS Windows

-   [Windows Git](http://www.davidkinder.co.uk/glulxe.html)

-   [Windows Glulxe](http://www.davidkinder.co.uk/glulxe.html)

-   [Windows Frotz](http://www.davidkinder.co.uk/frotz.html)

#### Mobile Devices

##### Andorid

-   [Twisty](https://bitbucket.org/sussman/twisty) — supports Z-code and Glulx story files.

-   [Text Fiction](http://www.onyxbits.de/textfiction) — supports Z-code (3, 5 and 8) story files.

##### iPhone

-   [iPhone Frotz](https://itunes.apple.com/us/app/frotz/id287653015)

##### PalmOS

-   [CliFrotz](http://zodiacstuff.sourceforge.net/clifrotz.html)

#### In-Browser Players

-   [Parchment](https://github.com/curiousdannii/parchment) — written in JavaScript, supports Z-Machine story files.

### Mappping Tools

Traditionally, IF maps are represented by boxes connected by lines, representing the various rooms and their directions connections. They are intended to represent movements in the adventure world locations, not a physical representation of its geography — but sometimes «realistic» maps are provided with the game feelies, for aesthetic reasons.

Mapping tools can be used for either manually drawing maps from scratch, or to automatically build a map by analizying a game session transcript (live or saved). Some tools offer both functionality.

Many of the tools presented here are now hosted at the IF-Archive — they are old and don’t have any longer a website of their own. To avoid direct linking to their binary archives, a link to the “Mapping Tools” index page at IF-Archive will be provided instead:

-   [The IF Archive » Mapping Tools](http://www.ifarchive.org/indexes/if-archiveXmapping-tools.html)

#### Cross Platform

-   [IFMapper](http://ifmapper.rubyforge.org/start.html) — A map drawing tool, written in Ruby, with lots of features, including automapping. Can read and save IFM files and Inform/TADS3 source code files. Exports to PDF.

-   [SVGmaps](http://www.ifarchive.org/if-archive/mapping-tools/SVGmaps.zip) — [2008] A JavaScript framework for producing IF maps using the standard Scalable Vector Graphics (SVG) language.

#### Mac OS

-   Cocoa Mapre — [2004] A tool for generating maps of Multi-User Dungeons on Mac OS X.

#### MS Windows

-   [AutoREALM](http://autorealm.sourceforge.net/) — [2006] A vector-based map drawing software (FOSS) designed for RPGs. Allows the creation of detailed full-color maps; ideal for the creation of elegant game maps where «room boxes» are superimposed on a realistic up-to-scale representation of the game world.

-   [Campaign Cartographer](https://secure.profantasy.com/products/cc3-plus.asp) — A commercial tool for drawing fantasy-style terrain maps — not the classic rooms/directions-based diagram IF maps, but ancient-looking «realistic» full-color maps, with villages, lakes, sea, forests. Execellent for creating feelies maps.

-   [Frobot Magic Adventure Mapper](http://www.ifarchive.org/indexes/if-archiveXmapping-tools.html) — [1998] Automapping tool for Windows 95.

-   GUEmap — Map drawing tool, can also generate directions for moving around the map. [GUEmap v1](https://www.cjmweb.net/GUEmap/download) [1998-1999] is Sharaware, [GUEmap v2](https://www.cjmweb.net/GUEmap/develop) [1998-2007] is now free and open source. Runs on Windows 95/98 or NT 4.0.

-   [IFM](https://bitbucket.org/zondo/ifm) (Interactive Fiction Mapper) — [1998–2014] Console/CMD executables available at [IF Archive](http://www.ifarchive.org/indexes/if-archiveXmapping-tools.html). IFM is a language for keeping track of gameplay progress, and a program for producing various different sorts of output using it, including automapping. See [online documentation](http://ifm.readthedocs.io/en/latest/contents.html) and [IFWiki](http://www.ifwiki.org/index.php/IFM).

-   [Informapper](http://www.ifarchive.org/indexes/if-archiveXmapping-tools.html) — [1996] A map drawing program for Windows, Spanish only user interface. Can export as a skeleton file for SINTAC. Can’t execute on modern versions of Windows.

-   [Map Maker](http://www.ifarchive.org/indexes/if-archiveXmapping-tools.html) — [1999] A Windows 95/98/NT world-building tool for visually designing maps to be converted as AGT, AGX, Hugo and TADS source code. Can still be executed under Windows 10.

-   [The Mapper](http://www.ifarchive.org/indexes/if-archiveXmapping-tools.html) — [1994] Automapping tool — comes as a `.COM` executable format. Can’t execute on modern versions of Windows.

-   [Trizbort](http://trizbort.genstein.net/) — For drawing Infocom-style maps. Automapping feature. Saves in XML, exports to PDF or PNG. Requires .NET 2.0.

#### Linux/\*nix

-   [Adventure Map Utility](http://www.ifarchive.org/indexes/if-archiveXmapping-tools.html) — [1994] A shell script that implements a domain-specific language for creating printable PostScript maps from plaintext input files.

-   [asciimapper](http://www.ifarchive.org/if-archive/mapping-tools/asciimapper) — [2005] A Perl script to create IFM maps from ASCII art maps. Intended as an easy way to draw a map and have it converted to IFM format.

-   [ifm2i7](http://www.ifarchive.org/indexes/if-archiveXmapping-tools.html) — [2008] A Perl program to convert maps in IFM format to Inform 7 source code.

-   [informap](http://www.ifarchive.org/if-archive/mapping-tools/informap.perl) — [1999] A perl script that draws maps out of Inform source code.

#### Mobile Devices

##### PalmOS

-   [IFmapper](http://www.ifarchive.org/indexes/if-archiveXmapping-tools.html) [2001]

## Collections

-   [Interaction Fiction Database](http://www.ifdb.tads.org)

-   [The Interaction Fiction Archive](http://www.ifarchive.org)

## Blogs

-   [Planet IF](http://planet-if.com) — Aggregation of posts from 50+ IF blogs

-   [Storycade](http://storycade.com)

-   [Emily Short's Interactive Storytelling](http://emshort.wordpress.com)

-   [Inky Path](http://inkypathmag.com) — Discussion of IF from a literary perspective. Discontinued but the archive is still accessible.

-   [Brass Lantern](http://brasslantern.org/)

## Competitions

-   [The Interactive Fiction Competition (IFComp)](http://www.ifcomp.org)

-   [Spring Thing Festival of Interactive Fiction](http://springthing.net)

## History

### Books

-   [Twisty Little Passages](http://nickm.com/twisty/)

-   [Creating Interactive Fiction with Inform 7](http://inform7.textories.com/)

### Documentaries

-   [Get Lamp](http://www.getlamp.com)

## Tutorials

## Conferences

## Meetups

-   [Museum of Art and Digital Entertainment's Monthly Interactive Fiction Meetup](http://themade.org/events)
