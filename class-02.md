## Reading: Basics of HTML,CSS & JS

**Text**
 
 The text on a webpage is made up of HTML tags that the computer can easily understand.
 You can use these tags to create:
 - Headings
 - Paragraphs
 - Bold, Italic, or emphasis in words on a page
 - Structural and semantic markup (or tags themselves)

The tags provide extra meaning and show users the structure for the page.
The types of tags used can be:
 - < h1 > thru < h6 > for the heading. h1 tags are used for the main heading and is only used once and the h2 thru h6 tags are used as subheadings throughout the page.
 - < p > is used for the paragraph on the page. By default, a browser normally shows a new paragraph on a new line, yet line breaks < br > are sometimes necessary for making the paragraph look neat.
 - < b > is used for bold characters
 - < i > is used for italic characters
 - < sup > is used for to contain characters that should be superscript such as the suffixes of dates or mathematical concepts like raising numbers to a certain power.
 - < sub > contains elements that should be subscript. COmmonly used with the foot notes or chemical formulas such as H2O.

white space is used to make code easier to read. Authors often add extra spaces or start elements on new lines.
When the browser comes across two or more spaces next to eachother, it only displays one space. When it comes across a line break it still treats it as a regular space. These white space collapsing can be used to indent code to make it easier to follow.

If you wanted line breaks inside the paragraph tag you have to use the tag < br > and to create breaks between themes you need to use the tag < hr >.
Content management systems and HTML editors like Dreamweaver usually have two views if the page you are creating:
 - A visual editor: ressemble word processors
 - A code view: shows the code created by the visual code editor so you can manually edit it.

Some text elements that are not intended to affect the structure of webpages, but they do add extra info to the pages. This is known as *Semantic Markup.*
In order to emphasis or show that the text is improtant you need to use these tags:
 - < strong > is used to show that the text is of strong importance.
 - < em > is used to emphasis text and it subtly changes the meaning of the sentence.

There are two tags used for marking up quotations:
 - < blockquote > is used for longer quotes that takes up an entire paragraph. You have to put this tag in between the paragraph tags.
 - < q > is used forshorter quotes that sit within a paragraph. Now this is not used often because browsers are supposed to put quotes around the < q > element and internet explorer does not do this.

Now abbreviations and acronyms are used with this tag: < abbr >
Citations and definations use thes tags:
 - < cite > used for when you reference a piece of work such as a book,film, or research paper. HTML5 cannot be used for a person's name, but it was allowed in HTML4.
 - < dfn > is used for defining instance of a new term.

< address > is used to contain contact details for the author or developer of a page.

In order to make changes to content you have to use these tags:
 - < ins > is used to show content that has been inserted into a document. (would usually have a line under it)
 - < del > is used to show text that has been deleted from a document. (would usually have a line through it)
 - < s > is used to indicate something that is no longer accurate or relevent.