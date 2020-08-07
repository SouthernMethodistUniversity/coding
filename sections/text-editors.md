
[<<< Previous](command-line-useful.md) | [Next >>>](cloud-vs-local.md)

# What do we mean by text editors?

## What does "text-based" mean?

For those of us comfortable reading and writing, the idea of "text-based" in the context of computers can seem a bit strange. As we start to get comfortable typing commands to the computer, it's important to distinguish "text" from word processed, desktop publishing (think Microsoft Word or Google Docs) in which we use software that displays what we want to produce without showing us the code the computer is reading to render the formatting. Plain text has the advantage of being manipulable in different contexts. 

Let's take a quick moment to discuss text and text editors.

### What is text?

Before we explain which program we'll be using for editing text, we want to give a general sense of this "text" we keep mentioning. For those of us in the humanities, whether we follow literary theorists who read any object as a "text," or we dive into philology, paleography, codicology or any of the fields [David Greetham](https://en.wikipedia.org/wiki/David_Greetham_(textual_scholar)) lays out in *Textual Scholarship*, "text" has its specific meanings. 

As scholars working with computers, we need to be aware of the ways plain text and formatted text differ. Words on a screen may have hidden formatting. Many of us grew up using Microsoft Word and don't realize how much is going on behind the words shown on the screen. For the purposes of communicating with the computer and for easier movement between different programs, we need to use text without hidden formatting.

![Word Doc](https://github.com/SouthernMethodistUniversity/coding/blob/master/images/worddoc.png)

If you ask the command line to read that file, this Word .docx file will look something like this

![Cat Word Doc](https://github.com/SouthernMethodistUniversity/coding/blob/master/images/CatWordDoc.png)

Word documents which look like "just words!" are actually comprised of an archive of extensible markup language (XML) instructions that only Microsoft Word can read. Plain text files can be opened in a number of different editors and can be read within the command line.

### Plain text

For the purposes of communicating with machines and between machines, we need characters to be as flexible as possible. Plain text includes characters of readable material but not graphical representation.

According to the [Unicode Standard](https://www.unicode.org/versions/Unicode6.1.0/), 

"Plain text is a pure sequence of character codes; plain Unicode-encoded text is therefore a sequence of Unicode character codes."

Plain text has a few main properties:

- "plain text is the underlying content stream to which formatting can be applied. Plain text is public, standardized, and universally readable."
- Plain text shows its cards -- if it's marked up, the markup will be human readable. Plain text can be moved between programs more fluidly and can respond to programmatic manipulations. Because it is not tied to a particular font or color or placement, plain text can be styled externally.

A counterpoint to plain text is rich text (sometimes denoted by the Microsoft rich text format ".rtf" file extension) or "enriched text" (sometimes seen as an option in email programs). In rich text files, plain text is elaborated with formatting specific to the program in which they are made.

**Note:** Software like Microsoft Word or Excel add formatting (and can sometimes changes made by the auto-formatting can introduce errors). "Excel errors happen all the time, simply because the software is often the first thing to hand when scientists process numerical data. [Scientists rename human genes to stop Microsoft Excel from misreading them as dates](https://www.theverge.com/2020/8/6/21355674/human-genes-rename-microsoft-excel-misreading-dates)

### Text editors

An important tool for programming and working in the command line is a text editor. A text editor is a program that allows you to edit plain text files, such as .txt, .csv, or .md. Text editors are not used to edit rich text documents, such as .docx or .rtf, and rich text editors should not be used to edit plain text files. This is because rich text editors will add many invisible special characters that will prevent programs from running and configuration files from being read correctly. 

While it doesn't really matter which text editor you choose, you should try to become comfortable with at least one text editor. Choosing a text editor has as much to do with personality as it does with functionality. Graphical user interfaces (GUIs), user options, and "hackability" vary from program to program. 

### Editors vs. IDEs

When it comes to editing text and writing code, you can use either a text editor or an IDE (Integrated Development Environment). Text editors tend to be more lightweight solutions, while IDEs try to provide a lot of features to help you write code and tend to target specific languages. There are a lot of exceptions to that description, but the distinction isn't that important. Just know that editors will sometimes describe themselves as IDEs, and that there's a slight difference in philosophy between them.

### Note about Special Characters
"Special characters include characters that are not found on a standard English-language keyboard or that are not one of the 128 characters of the US-ASCII character code set. Examples include characters with diacritics and special symbols, such as the copyright sign or an ampersand. How these characters are represented varies in HTML and XML." [UNL Center for Digital Research in the Humanities](https://cdrh.unl.edu/articles/basicguide/TEI) 
* More informtion on:[Characters, Glyphs, and Writing Modes](https://www.tei-c.org/release/doc/tei-p5-doc/en/html/WD.html)
* "TEI tags describe the characteristics of a given text. For example, TEI tags may be used to indicate paragraph and line breaks, pagination, and major divisions of a text such as volumes, chapters, and sections. In addition, tags may be placed around typographical characteristics such as text that is underlined, italicized, superscripted, etc., and around text that needs special emphasis such as foreign words, misspellings, proper names, etc." [UNL Center for Digital Research in the Humanities](https://cdrh.unl.edu/articles/basicguide/TEI) 
* Example: ["In transcribing a manuscript, it might be desirable to distinguish among three distinct forms of the letter r."](https://quod.lib.umich.edu/cgi/t/tei/tei-idx?type=HTML&rgn=DIV1&byte=281938)
* [Projects that use TEI](https://tei-c.org/Activities/Projects)

[<<< Previous](command-line-useful.md) | [Next >>>](cloud-vs-local.md)

----

[<<< Return to introduction](https://github.com/SouthernMethodistUniversity/coding)
