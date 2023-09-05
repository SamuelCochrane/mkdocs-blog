---
alias: null
cssClasses: embed-strict
date: 2022-11-28
dateModified: 2023-09-04
share: true
slug: digital-garden
stage: 🌱 Seedling
title: Digital Garden
---

# [[Digital Garden|Digital Garden]]

A digital garden represents a publicly accessible journal, usually a [[Zettelkasten|Zettelkasten]], where posts represent more of an "ongoing idea" than a finished & published "dead idea".

A note in a digital garden could be updated over the course of years, each time having new ideas added to further flesh it out. [[Art is never finished, merely abandoned]].

Digital gardening represents a mentality of building with the garage door up. Let people see what you're up to, poke their heads in, and reach out with ideas. 
This has some benefits for networking.
- It's easy, simple, and automatic - just keep taking the notes you're already taking
-   If you're building it, probably no one else has done this specific thing before. So there's a good chance you'll be one of the only quality search results when the next person comes along.

### Example Digital Gardens

- [GitHub - tanepiper/obsidian-garden: An Obsidian.md vault with best practices/examples](https://github.com/tanepiper/obsidian-garden)
-   [About This Website · Gwern.net](https://www.gwern.net/About#design)
	-   The revision history is kept in git; individual page sources can be read by appending to their URL
	-   Gwern.net [is implemented](https://www.gwern.net/Design#tools) as a static website compiled via Hakyll from Pandoc Markdown and hosted on a dedicated server (due to expensive cloud bandwidth).
	-   It stands out from your standard Markdown static website by aiming at good typography, fast performance, and advanced hypertext browsing features (at the cost of great implementation complexity); the [4 design principles](https://www.gwern.net/Design#principles) are: aesthetically-pleasing minimalism, accessibility/​​progressive-enhancement, speed, and a ‘structural reading’ approach to hypertext use.
	-   Unusual features include the monochrome esthetics, [‘sidenotes’](https://www.gwern.net/Sidenotes) instead of footnotes, efficient [dropcaps](https://en.wikipedia.org/wiki/Initial)⁠/​​smallcaps, collapsible sections, automatic inflation-adjusted currency, Wikipedia-style link icons & infoboxes, custom syntax highlighting, extensive local archives to fight linkrot, and an ecosystem of “popup”/​​“popin” annotations & previews of links for frictionless browsing—the net effect of hierarchical structures with collapsing and instant popup access to excerpts enables iceberg-like pages where most information is hidden but the reader can easily drill down as deep as they wish.
	-   Also discussed are the [many failed experiments](https://www.gwern.net/Design#abandoned) & design changes made along the way.
-   [Notes | Chase McCoy](https://chasem.co/notes)
	-   [GitHub - chasemccoy/www: 🏡🌱 My website, blog, and digital garden.](https://github.com/chasemccoy/www)
-   [Richard Ng | Digital Garden](https://richard.ng/garden)
-   "The Andy System" [About these notes](https://notes.andymatuschak.org/)
	-   Andy built his own website code to make a public facing web interface for this. I'm crushing on him super hard.
	-   or he could have basically just used [GitHub - mathieudutour/gatsby-digital-garden: 🌷 🌻 🌺 Create a digital garden with Gatsby](https://www.remnote.com/doc/jsYz3AmXL9QGsadKf) 🙄
- Maggie Appleton's Digital Garden ^yhg5y0
	-   [GitHub - MaggieAppleton/maggieappleton.com-V2: A digital garden built with Next.js, React, and MDX. Featuring loosely opinionated notes, half-formed ideas, and content that is always growing.](https://github.com/MaggieAppleton/maggieappleton.com-V2)
	- [Maggie Appleton](https://maggieappleton.com/)

### Templates/Prefabs/Systems

- [GitHub - flowershow/flowershow: Publish your digital garden, docs or any markdown based site easily, quickly and elegantly](https://github.com/flowershow/flowershow)
-   [GitHub - maximevaillancourt/digital-garden-jekyll-template: Start your own digital garden using this Jekyll template 🌱](https://github.com/maximevaillancourt/digital-garden-jekyll-template)
	-   ⭐use [Roam Research](https://www.remnote.com/doc/BLiPSvJRy7EHEHKCv) as a backend, [GitHub - DoomHammer/roam-to-git at roam-to-garden](https://github.com/DoomHammer/roam-to-git/tree/roam-to-garden)Automatic RoamResearch backup to a digital garden (queries the API every 4hrs and pushes changes to md repo)
		-   [GitHub - MatthieuBizien/roam-to-git: Automatic RoamResearch backup to Git](https://github.com/MatthieuBizien/roam-to-git)
			-   edit browser code:
			-   [steps recorder for Puppeteer : Headless Recorder - Chrome Web Store (generate pupeteer code automatically)](https://www.remnote.com/doc/AyWRg5xhLqRiRnoXE)
		-   assuming I can get this working for [RemNote](https://www.remnote.com/doc/NaPxuAdqmdXufA9PD) , seems like a nice way to automatically publish and keep everything in one place (just tag articles with [publish] or [redbrookpublish] and they're added to the respective site)
-   [GitHub - mathieudutour/gatsby-digital-garden: 🌷 🌻 🌺 Create a digital garden with Gatsby](https://github.com/mathieudutour/gatsby-digital-garden)
	-   [fetch-roamresearch](https://github.com/mathieudutour/gatsby-digital-garden/blob/master/packages/fetch-roamresearch): Export and download a Roam Research database
	-   [gatsby-source-roamresearch](https://github.com/mathieudutour/gatsby-digital-garden/blob/master/packages/gatsby-source-roamresearch): Source plugin for pulling data into Gatsby from Roam Research.
	-   [gatsby-remark-double-brackets-link](https://github.com/mathieudutour/gatsby-digital-garden/blob/master/packages/gatsby-remark-double-brackets-link): Transform `[[page]]` into a proper link.
	-   [gatsby-remark-double-parenthesis-link](https://github.com/mathieudutour/gatsby-digital-garden/blob/master/packages/gatsby-remark-double-parenthesis-link): Transform ((page)) into a proper link.
	-   [react-stacked-pages-hook](https://github.com/mathieudutour/gatsby-digital-garden/blob/master/packages/react-stacked-pages-hook): Manage a stack of pages in Gatsby.
	-   [gatsby-transformer-markdown-references](https://github.com/mathieudutour/gatsby-digital-garden/blob/master/packages/gatsby-transformer-markdown-references): Extract references between markdown nodes.
	-   [gatsby-theme-garden](https://github.com/mathieudutour/gatsby-digital-garden/blob/master/packages/gatsby-theme-garden): A Gatsby theme bundling all of the above packages.
-   [GitHub - ppeetteerrs/obsidian-zola: A no-brainer solution to turning your Obsidian PKM into a Zola site.](https://github.com/ppeetteerrs/obsidian-zola) A free (but better?) alternative to [[Obsidian#Obsidian Publish|Obsidian > Obsidian Publish]].

### Info

-   [How to set up your own digital garden - Ness Labs](https://nesslabs.com/digital-garden-set-up)
-   🌟[GitHub - MaggieAppleton/digital-gardeners: Resources, links, projects, and ideas for gardeners tending their digital notes on the public interwebs](https://github.com/MaggieAppleton/digital-gardeners)
-   [Digital Gardening for Non-Technical Folks](https://maggieappleton.com/nontechnical-gardening)
- [Tending Evergreen Notes in Roam Research](https://maggieappleton.com/roam-garden) [[Roam Research|Roam Research]]
