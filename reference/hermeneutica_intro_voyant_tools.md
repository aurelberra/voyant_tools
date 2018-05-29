> This document is an almost unmodified version of the [original Hermeneuti.ca tutorial](http://hermeneuti.ca/intro-workshop). It is archived here for reference. While many links are dead, the platform is very much alive… (Aurélien Berra, 2018-05-29)

# Introduction to Voyant Tools

![Voyant logo](voyant-logo_0.png)

This script for a workshop is designed to show you how to use the Voyant Tools text analysis environment. It will run between one and two hours.

[Voyant Tools](http://voyant-tools.org/) is part of a larger project with the book [Hermeneutica](http://hermeneuti.ca/) (MIT Press, 2016).

## Outline

- Looking at text tool
- Using an environment of tools
- Try your own text
- Getting help

## Look at this [word cloud](http://voyant-tools.org/tool/Cirrus/?corpus=frankenstein&toolFlow=contexts)

- What text do you think it is a cloud for?
- What features are metrical (based on measuring the text in some way)? How are the other features generated?
- What words are missing?

Play with it yourself. Or try this cloud for [Shakespeare](http://voyant-tools.org/tool/Cirrus/?corpus=shakespeare&stopList=stop.en.taporware.txt&toolFlow=contexts).

## Using an environment of tools

Now let’s look at this [Voyant display](http://voyant-tools.org/?corpus=frankenstein&stopList=stop.en.taporware.txt). This is the default skin that combines a bunch of tools that work
together. To use this more complex display you need to understand views that combine tools:

- Each tool has a panel that can be minimized/maximized.
- Each panel has options.
- Each panel has ways you can manipulate it or search it.
- Panels will trigger updates in other panels.

Try playing with the default environment of Voyant with a single text and then with a [Shakespeare corpus](http://voyant-tools.org/?corpus=shakespeare). Note the extra panels when you have a collection of texts.

## Try your own text

Now you are ready to load your own text into Voyant. Go to [http://workshop.voyant-tools.org](http://workshop.voyant-tools.org/) (temporary) or [http://voyant-tools.org](http://voyant-tools.org/).

Voyant gives you a number of ways to index a text for studying it with Voyant:

- You can **paste** in text.
- You can type in a **URL** for Voyant to get. For example you could run Voyant on my blog [http://theoreti.ca](http://theoreti.ca/).
- You can **upload** a text.
- You can **open** one of the corpora we have preloaded using the Open button.

## Things to look at

There are a number of extensions and variants of Voyant that you might want to know about:

- <http://v1.voyant-tools.org/> is version 1.0 of Voyant if you liked that more or need some feature there.
- <http://voyant-tools.org/?lang=fr> is a French version of Voyant (there are [other language versions](http://voyant-tools.org/docs/#!/guide/languages) coming online as colleagues translate the interface).
- [Hermeneutica](http://hermeneuti.ca/) shows examples of how Voyant panels can be dropped into online essays.
- <http://voyant-tools.org/dtoc/?corpus=regenerations&curatorId=regenerations> is a specialized interface of Voyant for a volume that uses underlying markup.
- <http://voyant-tools.org/?corpus=humanist&view=scatterplot> is a different view with text mining tools.
- <http://voyant-tools.org/catalogue/cwrc/?facet=facet.extra.collection,facet.author> is a large faceted corpus selection tool that launches Voyant on a subset.
- <http://dream.voyant-tools.org/> is an interface to create worksets from the TCP EEBO Phase 1 collection.
- [@VoyantTools](https://twitter.com/VoyantTools): see what other people are doing with Voyant on our Twitter feed.

## Getting help

The Guide for Voyant is at <http://voyant-tools.org/docs/#!/guide/start>.

The main URL for Voyant Tools is <http://voyant-tools.org/>, though there are other URLs that can be used:

- <http://temp.voyant-tools.org/> is a server used sometimes, but it's a temporary server so we only turn it on if needed so please avoid linking to it.
- <https://github.com/sgsinclair/VoyantServer/#voyant-server> where you can download Voyant server for your own machine and not depend on our server. This runs locally on your machine.

Or contact Geoffrey Rockwell (<geoffrey.rockwell@ualberta.ca>) or Stéfan Sinclair (<stefan.sinclair@mcgill.ca>).

Follow us on Twitter at [@VoyantTools](https://twitter.com/VoyantTools).
