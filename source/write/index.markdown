---
layout: page
title: "Write on Märzwasser!"
date: 2014-01-07 13:12
sharing: true
footer: true
author: <a rel="author" href="http://chymera.eu">Horea Christian</a>
license: <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
---

Märzwasser helps you organize your writing, co-author literary texts, and make your work open, free, and accessible.
Here's how You can become a part of the "Collaborative Literature Framework".

If you have any issues at all with following the instructions below, please tell us via [our issue tracking system](https://github.com/TheChymera/mw/issues) -
you'll have to register on [GitHub](http://en.wikipedia.org/wiki/Github) for this (which is easy, fast, free, and will not spam your inbox).
Once you tell us your issue we will start helping you immediately! 

## Contribute New Texts

If you have a literary creation which you would like to publicize via our website - and are enthusiastic about potential contributions from other authors - 
you can easily make your texts a part of Märzwasser.
For this you should follow these simple steps:

1. Create a GitHub account [here](https://github.com/join).
2. Sign in to your GitHub account.
3. Fork [our main repository](https://github.com/TheChymera/mw) - via the GitHub "fork" button in the upper right.
4. Navigate to ```mw/source/_posts``` in the repository fork you now have on your account (by clicking on the folders).
5. Create a new empty file in that location (via the "create a new file here" button - it's located right after the directory path).
6. Rename your file and add content to it based on the [markdown](http://en.wikipedia.org/wiki/Markdown#Example) syntax examples seen in any other files in that directory.
7. Submit a pull request via [the respective button](https://help.github.com/articles/creating-a-pull-request) in your GitHub interface.

Every new file should contain a preamble which looks like this:

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

The date should indicate when you wrote the text; and ```layout: post``` and ```comments: true``` should generally remain unchanged.
We also encourage you to keep the ```license: ``` field unchanged as exemplified above - though we further detail licensing on [our "about" page]({{ root_url }}/about).

## Make an Edit

If you feel you can in any way improve the work of another author and would like to contribute to his text - you should follow these steps
(very similar to the above):

1. Create a GitHub account [here](https://github.com/join).
2. Sign in to your GitHub account.
3. Fork [our main repository](https://github.com/TheChymera/mw) - via the GitHub "fork" button in the upper right.
4. Navigate to ```mw/source/_posts``` in the repository fork you now have on your account (by clicking on the folders).
5. Find the file you want to edit and make the edits you want.
6. Submit a pull request via [the respective button](https://help.github.com/articles/creating-a-pull-request) in your GitHub interface.

When you contribute to a text you should add yourself (if you are not already on the list) to the list of authors in the preamble - example: ```author: "A. U. Thor, Contribu Tor, Your Name"```.
You should not edit the license unless you have verified that there is a consensus about your proposed license change among all other authors of the work.

## For the Hackers among You

If you are familiar with Git, GitHub, and Octopress (and feel comfortable hacking stuff here and there) you may do the following instead:

1. Install Octopress as described [here](http://octopress.org/docs/setup/).
2. Optionally: Install [Königspress](https://github.com/TheChymera/Koenigspress), our Octopress theme of choice.
3. Copy the files from [our main repository](https://github.com/TheChymera/mw) on top of your Octopress install.
4. Prune and select the files tracked in git (via ```git rm --cached``` and ```git add``` respectively) to include only and all of the locations we include.

This will actually give you a working copy of our website!
You may now push to and pull from our repository, edit, and even mirror our content as you like.


<sup>Browse the history of this file *or* find static versions to cite via [its GitHub page](https://github.com/TheChymera/mw/blob/master/source/write/index.markdown)!</sup>

