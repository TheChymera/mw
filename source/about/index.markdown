---
layout: page
title: "About Märzwasser"
date: 2013-12-28 16:10
sharing: true
footer: true
author: <a rel="author" href="http://chymera.eu">Horea Christian</a>
license: <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
---

Märzwasser \[mεrtsˈva.s&"\] - the collaborative literature framework - is built to allow authors to improve on each other's literary work.
We strive to bring the benefits of social content creation and free licensing (as seen in the [FOSS](http://en.wikipedia.org/wiki/FOSS) world) to the world of literature.
Here we clarify a few of the concepts which are fundamental to our framework.

## Version Control
To keep track of the authorship of every single contribution we use the best and greatest tool for [version controlling](http://en.wikipedia.org/wiki/Revision_control) text documents:
[Git](http://en.wikipedia.org/wiki/Git_(software).
To make our usage of this system as open to the public and as accessible to less-computer-savvy authors as possible, we encourage managing Git repositories via the very user-friendly website [GitHub](http://en.wikipedia.org/wiki/Github).

## Workflow Concept

Git is distributive - meaning that as far as the text version management system is concerned, diverging versions of the same file can coexist and are equal in importance.
Git permits divergent editing (whereby a text can slowly be transformed into two or more very different texts),
and also permits convergent editing (whereby similar texts, or texts which complement each other well in the view of an editor can be merged into a single file).
In the jargon of Git, divergent editing is called "forking" and convergent editing "merging".

The distributive model of Git is based on each user having their own repository (personal copy of all the texts) in which they decide which changes to make.
Changes made to a text (along with the attribution to the editor) may be "pulled" (adopted) by other editors if these changes find resonance with them -
if the changes find no critical acclaim whatsoever in the community of editors, however, they remain confined to only the one repository in which they were created.
Editors can also follow two or more divergent developments of the same text in their repositories via what Git calls "branches" - which are in simple terms sub-repositories of a repository. 

For better comprehension of the Git workflow you can take a look at a couple of real-life graphical maps of Git edit networks - [here](https://github.com/stevenbristol/lovd-by-less/network), [here](https://github.com/wycats/merb-plugins/network), or [here](https://github.com/sr/git-wiki/network).
For an even better and in-depth understanding of Git we would kindly recommend the [reference manual](http://git-scm.com/documentation).

## Licensing

For all of this to work, you - as an author and/or contributor - have to license your work in a way which also allows others to contribute to it.
There are many types of licenses which permit this - and of these we would recommend the [Creative Commons](http://en.wikipedia.org/wiki/Creative_Commons) license suite, as we believe it is best suited for creative literary work.

Creative Commons offers you the possibility to fine-tune your license according to whatever details seem important to you.
They provide a nice and simple flowchart-type license generator [on this web page](http://creativecommons.org/choose/).

Choosing an appropriate license is - however - not as simple as it may seem.
You should take into consideration how limitations which you impose could impair others' freedom to contribute to your texts or to share them as a [free culture works](http://creativecommons.org/freeworks).
Also, you should spare a thought on how freedoms which you grant could be used to bypass you in for-profit publishing.

Of all the Creative Commons licenses, we advise you to use the [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
You should, however, bear in mind that this license (awesome as it otherwise is) could in principle be used by publishers to publish your work and make a profit without awarding you any royalties.
Should this make you very weary, we would recommend the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/) as a passable second choice.
A drawback here is that this license could impair sharing your work on this website - or other websites - in case we or their respective owners decide to publish ads on them.
If you submit a non-commercially licensed work to our site, we would like you to understand that we reserve our right to publish ads on our website at any point and without notice.

You can select your preferred license when you write a text in the ```license``` section of the preamble.

{% codeblock A preamble example: lang:text %}
---
layout: post
title: "Lorem"
date: 2013-12-28 17:49:17 +0200
comments: true
categories: [fiction, non-fiction, horror, fantasy, whatever]
author: <a rel="author" href="http://your.website.org">A. U. Thor</a>
license: <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
---
{% endcodeblock %}


<sup>Browse the history of this file *or* find static versions to cite via [its GitHub page](https://github.com/TheChymera/mw/blob/master/source/about/index.markdown)!</sup>
