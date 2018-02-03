<!-- TITLE: Home -->
<!-- SUBTITLE: A quick reference guide to all things TeraRecon -->

# About TeraWiki
You can even edit the wiki yourself! Its written completley in [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet "Markdown Cheat Sheet"). That means you don't have to know the first think about coding to even use this page! It also has a different kind of database than many people are use to. The database itself is called MongoDB and it is a flavor of NoSQL this means that it's a non-relational database that doesn't enforce a schema. It makes it really easy to do things like search quickly for any word above and find the resulting page.  

If you would like to know more about the specifics of how this wiki works then keep reading. Otherwise start your search on the left side of the screen in the navigation panel.



# Styling with TeraWiki
## Bold Text
To make a text in bold, simply put double asterisks ** before and after the desired text.

`This is a **bold** move` :arrow_right: This is a **bold** move.

## italics
To make a word italicized simply put an asterisk * before and after the desired text.
`This is *crazy*` :arrow_right: This is *crazy*

## strikethrough
To make a text in strikethrough, simply put double tildes ~~ before and after the desired text:
`TeraWiki is ~~terrible~~ AMAZING!` :arrow_right: TeraWiki is ~~terrible~~ AMAZING!

## Headers
To define a line as a header, simply put a hash sign # at the beginning. The amount of consecutive # you insert defines the level of the header.

```text
# H1
## H2
### H3
#### H4
##### H5
###### H6
```

Example:


```text
# Section A

## Sub-section A.1

### Sub-sub-section A.1.1

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed at sapien at odio fringilla lobortis.

# Section B

Etc...
```
In the above example, Section A and B are top level headers and Section A has a sub-header (A.1), which contains a sub-header (A.1.1).



## Blockquotes
Blockquotes generally define quotations from other sources but on TeraWiki they can have multiple uses for anything from data diferentiation to showcasing.

To start a block quote all you need to do is begin your line with >

>This is a blockquote!

You can even write multiline blockquotes by continuing your next line with another >

>This is a multiline blockquote
>
>It's really easy to use!

Another fun thing to do is to style the blockquote. There are 5 block quote styles:

>Default

>Info
{.is-info}

>Success
{.is-success}

>Warning
{.is-warning}

>Danger
{.is-danger}

Simply add the desired styling class below your blockquote:

```text
> Default

> Info
{.is-info}

> Success
{.is-success}

> Warning
{.is-warning}

> Danger
{.is-danger}
```

