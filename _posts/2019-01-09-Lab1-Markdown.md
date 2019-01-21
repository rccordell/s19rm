---
layout: post
title: "Lab #1: Markdown"
tags: [lab, fieldbook]
author: rccordell
permalink: /labs/Lab1-Markdown/
---

## Lab Overview

Your [fieldbook assignment](/assignments/fieldbook) constitutes the central, ongoing work of your semester where you will record your ideas about our readings in *bibliographic annotation* entries and think through the work of our humanities laboratories in *lab report* entries. You will gather all of these materials in a repository on [Github](https://github.com/). You will write using the Markdown syntax, which I describe below and which we will discuss in detail during today's laboratory.

## Lab Report 1 Prompt

Your first lab report has a wide mandate, and will give you the chance to experiment with weaving together your ideas from our first week's reading and discussion with a thoughtful engagement with our first laboratory. Do not try to discuss every reading or point you might; instead, choose 1-2 readings and one central idea to dig into. Use your lab report to bring together theory and praxis, to begin understand *doing* as a critical and intellectual practice intimately related to *thinking* or *writing*. In this case, what might Markdown have to say to our burgeoning understanding of media and materiality? 

### Required Software

+ A [Github](https://github.com/) or [Github Education](https://education.github.com/) account
+ [Github Desktop](https://desktop.github.com/)
+ a text editor, and ideally a Markdown-aware one (see lists below)

## Working with Github

You may sign up for a free Github account or, if you would like the option to create private repositories, apply for a free Pro account under [Github Education](https://education.github.com/). I recommend the latter, which is available to you while you are a student.

We will discuss some of the reasons I want you to try Github in this lab, but in brief:

1. It's a convenient way to store work that includes writing and, as we will need later in the semester, computer code, and to share that work easily with others: in this case, your colleagues and instructor.
2. It will help us learn about version control: in short, Github saves each instance of your work so that you can return to earlier versions simply, as well as giving you the capacity to collaborate asynchronously with other writers/coders.
3. It will give us a good platform for exploring writing in Markdown, which is what this lab will largely focus on.

Once you have signed up for your Github account, we will begin discussing methods for contributing—or adding files—to it. You might consider downloading the [Github Desktop](https://desktop.github.com/) application to make contributing to your repository simple. 

Essentially, however, you will be creating a folder on your own computer in which you will create new Markdown files, and which you will periodically *commit*, or sync, to Github. This way you can write locally but regularly post your work in a way I will be able to access (as well as any others you wish). 

## Filenames and Headers

You should name your files following a very specific convention, which I also outline in the fieldbook assignment. 

> *For bibliographic annotation entries:*
> 
> `YYYY-MM-DD-bibliographic-WHAT-WORDS-YOU-WANT.md`
> 
> *For lab report entries:*
> `YYYY-MM-DD-labreport-WHAT-WORDS-YOU-WANT.md`

Each file should begin with a header following this convention:

*For bibliographic annotation entries:*

```
---  
layout: post  
title: "TITLE HERE"  
tags: [bibliographic annotation, fieldbook]  
author: YOUR NAME HERE 
---
```  

*For lab report entries:*

```
---  
layout: post  
title: "TITLE HERE"  
tags: [lab report, fieldbook]  
author: YOUR NAME HERE 
---
```  

## Composing in Markdown

In this class I want you to be thoughtful about the medium in which you choose to write. We will do our writing for this class not in Word or another WYSIWYG (What You See Is What You Get) editor, but in a range of possible application and using the Markdown syntax. I don't expect every one of you to become Markdown devotees (though a few often do in my classes), but I do expect you to attend thoughtfully to your own technologies and habits of composition by exploring an alternative mode to what you are likely used to. 

### What is Markdown?

Markdown is a lightweight standard for writing in plain text while encoding the **structure of your document** for later representation in a format like Word, PDF, or HTML. If you have ever marked up a text using HTML or XML tags, Markdown works quite similarly, but uses simple typographical symbols to encode text rather than longer HTML  or XML tags. There are a number of *affordances* to working in Markdown, including:

1. **Simplicity.** Because Markdown is a plain-text system of encoding structural elements typographically—rather than, as in proprietary formats like `docx`, though hidden, underlying code—Markdown files are small in size and simple to compose. You do not need to interrupt your writing to format your document while writing in Markdown.
2. **Flexibility.** When writing in Markdown you encode directions for styling your text, but you do not style it directly. Because of this, an `md` file can be easily converted to many other standard file types, including `html` or `pdf`. You can easily convert a single `.md` file into a range of other formats, giving you flexibility when you want to publish your writing. 
3. **Durability.** Unlike files composed in specific version of proprietary software, Markdown files are, essentially, plain text files. This means they can be opened by a wide range of applications and they will look essentially the same, and that they are not subject to the vicissitudes of software updates or platform dependencies. You can open and edit a Markdown file on virtually any computer, and you will likely be able to do well into the future. Even if the conventions of Markdown are no longer understood, the central text you write in it should remain widely compatible and portable.
4. **Mobility.** Because Markdown is composed using basic typographical characters, it's very easy to use on mobile platforms such as phones or tablets. For example, my favorite note-taking app, [Bear](https://bear.app/) allows you to compose in Markdown and access your notes through a Desktop and Mobile interface. There are a number of applications for composing in Markdown while on the go, including mobile versions of some of the desktops apps I recommend here.   

As with any medium, of course, there are also *limitations* to writing in Markdown, such as:

1. You have less granular control over the appearance of your text than you would in a full featured word processor. In order to ensure the flexibility and durability of Markdown, its grammar is relatively constrained. While you can indicate text should be `bold` or formatted in a `numbered list` using Markdown, for instance, you could indicate that one paragraph's font should be 2 points larger than another. 
2. You typically have to convert Markdown files into another format before publication. This is not *quite* true on the web, where some frameworks like GitHub Pages can understand Markdown (as expressed in a Jekyll website) directly, but usually the production stage for a Markdown document involves converting your `md` file into another format, thus converting Markdown's structural encoding into actual stylistic representation.

### Markdown References

Below I will describe the most common Markdown syntax, but for additional reference you can consult:

+ The [Markdown Wikipedia page](https://en.wikipedia.org/wiki/Markdown), which includes a very handy chart of the syntax.
+ John Gruber's [introduction to Markdown](https://daringfireball.net/projects/markdown/syntax). Gruber developed the standard and knows what he's talking about!
+ This [interactive Markdown tutorial](http://www.markdowntutorial.com/), which will teach you the syntax in a few minutes.
+ You can also download [the Markdown versions of our class website pages](https://github.com/rccordell/s19rm) (all generated directly from Markdown) or [the Markdown for this very lab](https://github.com/rccordell/s19rm/blob/master/_posts/2019-01-09-Lab1-Markdown.md) if you'd like to compare what you see in your browser with the marked-up text that created it (click the `Raw` button to see the Markdown [without GitHub's styling](https://raw.githubusercontent.com/rccordell/s19rm/master/_posts/2019-01-09-Lab1-Markdown.md)).

In short, in Markdown your text will not include any visible stylistic variations such as italics or bold text; Markdown is a *plain text* format. However, many Markdown Editors will be able to preview the way your documents will look like when they're styled.

### Applications for Writing in Markdown

One advantage to this flat-text format is that you can write valid Markdown in many, many editors, including the free text editors (such as TextEdit on the Mac or Wordpad on the PC) that come with most computers. You can also write in Markdown in some rich text editors such as [Scrivener](https://www.literatureandlatte.com/scrivener.php), though their support for the standard can be uneven. 

There are many dedicated Markdown composition applications with additional features, such as syntax highlighting or the ability to preview what your documents. 

#### Free Markdown Applications:

+ [Macdown](http://macdown.uranusjr.com/) (Mac)
+ [Mou](http://25.io/mou/) (Mac)
+ [Markdownpad](http://markdownpad.com/) (Windows XP-8)
+ [Markdown Edit](http://markdownedit.com/) (Windows)
+ [Ghostwriter](http://wereturtle.github.io/ghostwriter/) (Windows & Linux)
+ [Remarkable](https://remarkableapp.github.io/) (Linux)
+ [Hashify](http://hashify.me/IyBUaXRsZQ==) (online) 
+ a bit more complicated to get started with, but [Atom](https://atom.io/) is more full-featured than some of those above (Mac, Windows, Linux)
+ It's not specifically a Markdown application, but [Prose.io](http://prose.io/) allows you to edit files in a Github repository and commit them all online.

#### Paid Markdown Applications

They can be pricey, but there are some beautifully-designed, paid Markdown-writing applications out there. I can't list them all, but here are two popular ones:   
  
+ [Ulysses](https://ulysses.app/) (Mac only) is beautifully designed and a joy to use. It was my go-to application for awhile but I moved away from it because of its non-standard implementation of a few Markdown elements, such as links and images. Others don't like their subscription payment model.
+ My current, (cross platform_ favorite is [iA Writer](https://ia.net/writer). It is also well designed, though not quite as elegant as Ulysses. But it requires only one payment to use and implements Markdown in a standard way, so that my writing is more broadly compatible with other systems. 

To compose pages and blog posts for Jekyll using these desktop applications, you will need to sync a local folder on your computer to your Github repository.

### Markdown Syntax

Here are the very basics for writing in Markdown. If you use one of the editors above with a preview feature, you'll be able to see what you're doing as you type.

1. If you want your text to be italicized, then *enclose it in single asterisks* or _in underlines_. (i.e. \*enclose it in single asterisks\* or \_in underlines\_).
2. If you want your text to be bold, then **enclose it in double asterisks**. (i.e. \*\*enclose it in double asterisks\*\*).
3. To start a new paragraph, simply hit return twice, so that you see a single line space in between paragraphs.
4. To start a new line without a paragraph break, add two spaces to the end of the first line and then hit return once.
5. To create a hyperlink, enclose the [words you want linked in brackets and the link in parentheses following](http://ryancordell.org/). 
	i.e. [words you want linked in brackets and the link in parentheses following]\(http://ryancordell.org/\).   

You can also create headlines of descending sizes, lists (numbered or bulleted), footnotes, block quotations, embedded images, and more. See the reference materials above for details on these other elements.