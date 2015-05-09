privattest
==========

wird wieder gelöscht
aber erst nachdem ich das mal lokal geclont habe

* * * 

# Markdown Demo
hier soll demonstriert werden wie `markdown`-Dateien in verschieden **Dialekten** und **stylesheets** funtionieren.

Bei den Dialekten gitbt es

* »normales« `markdown` (1)
* `markdown redcarped` (2)

Bei den Stylesheets erscheint mir am besten meine derzeitige `github`-Einstellung in `Textmate`. Die `md`-Dateien auf `bitbucket` zeigen aber einen anderen *Style*.

## Verschachtelte Listen

1. Lists in a list item:
    - Indented four spaces.
        * indented eight spaces.
    - Four spaces again.
2.  Multiple paragraphs in a list items:
    It's best to indent the paragraphs four spaces
    You can get away with three, but it can get
    confusing when you nest other things.
    Stick to four.
 
    We indented the first line an extra space to align
    it with these paragraphs. In real use, we might do
    that to the entire list so that all items line up.
 
    This paragraph is still part of the list item, but it looks messy to humans. So it's a good idea to wrap your nested paragraphs manually, as we did with the first two.
 
3. Blockquotes in a list item:
 
    > Skip a line and
    > indent the >'s four spaces.
 
4. Preformatted text in a list item:
 
        Skip a line and indent eight spaces.
        That's four spaces for the list
        and four to trigger the code block.

Bis hierher war alles noch gut und praktisch gleich. Es wurden ausschließlich `spaces` verwendet.

Jetzt möchte ich den Listen Überschriften zufügen

### 1. das sit Mist:
    und weiter
    
    und weiter

### GitHub Flavored Markdown:

Wird offensichtlich auch von `bitbucket` verwendet, denn dort geht das hier alles, wenn auch das CSS dort etwas unglücklich ist, zum Beispiel wegen der Abstände in Listen (siehe oben).

#### Multiple underscores in words ~~geht gar nicht bei mir~~

Where Markdown transforms underscores (`_`) into italics, GFM ignores underscores in words, like this:
	

	wow_great_stuff
	do_this_and_do_that_and_another_thing.

+ wow_great_stuff
+ do_this_and_do_that_and_another_thing.

Apropos: Textmate kommt damit aber nicht klar!

#### Durchgestrichen ~~geht aber~~

    ~~Mistaken text.~~

ergibt: ~~Mistaken text.~~

## Tabellen

| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| ---------:|
| col 3 is      | some wordy text |  1600,00 €|
| col 2 is      | centered        |    12,95 €|
| zebra stripes | are neat        |     1,-- €|


