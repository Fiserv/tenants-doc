# Writing standards

On this page:

[Abbreviations](#abbreviations-and-acronyms)

[Active voice](#active-and-passive-voice)

[Articles](#articles)

[Bias-free communication](#bias-free-and-inclusive-communication)

[Bullet list](#bullet-list)

[Capitalization](#capitalization)

[Code formats](#code-formats)

[Company names and logos](#company-names-and-logos)

[Content organization](#content-organization)

[Dashes—em dash and en dash](#dashes-em-dash-and-en-dash)

[Dates](#dates)

[Error messages](#error-messages)

[Folder and file naming conventions](#folder-and-file-naming-conventions)

[Headings and subheadings](#headings-and-subheadings)

[Images](#images)

[Inclusive names and secure data](#inclusive-names-and-secure-data)

[Informal tone](#informal-tone)

[Information classification](#information-classification)

[Links—Cross-references and hyperlinks](#links-cross-references-and-hyperlinks)

[Line breaks](#line-breaks)

[Mouse terminology](#mouse-terminology)

[Notices—Notes, tips, warning, and important](#notices-notes-tips-warning-and-important)

[Numbers](#numbers)

[Numbered or ordered lists](#numbered-or-ordered-lists)

[Parallel structure](#parallel-structure)

[Parentheses](#parentheses)

[Person](#person)

[Prepositions](#prepositions)

[Punctuation](#punctuation)

[REST API formats](#rest-api-formats)

[Spellings](#spellings)

[Tense](#present-tense)

[Text formats](#text-formats)

[Tooltips](#tooltips)

[Verb forms](#verb-forms-in-reference-documentation)

[Words and sentences](#words-and-sentences)

## Building the Fiserv brand

[Fiserv voice for developers](https://confluence.corp.clover.com/display/DEVREL/Clover+voice+for+developers)

[Fiserv tone for developers](https://confluence.corp.clover.com/display/DEVREL/Clover+tone+for+developers)

[Developer announcement guidelines](https://confluence.corp.clover.com/display/DEVREL/Developer+Announcement+Guidelines)

[Sample code]((https://confluence.corp.clover.com/display/DEVREL/Sample+code)

[Video Style Guide]file:///display/DEVREL/Video+Style+Guide

[Standard word list](#standard-word-list)

[Active product list](https://fiservcorp.sharepoint.com/sites/fuel/toolbox/color-me-orange/Documents/Naming/Active%20Product%20List.pdf)—updated monthly—approved Fiserv product and service names with trademark symbols

## Recommended resources

Google > [Developer documentation style guide](https://developers.google.com/style)

Microsoft Style Guide > [Code Examples](#code-examples)](https://docs.microsoft.com/en-us/style-guide/developer-content/code-examples)

Microsoft Style Guide > [Format](#format)](https://docs.microsoft.com/en-us/style-guide/developer-content/formatting-developer-text-elements)

Microsoft Style Guide > [Reference documentation](#reference-documentation)](https://docs.microsoft.com/en-us/style-guide/developer-content/reference-documentation)

Apple Style Guide > [Technical notation](https://help.apple.com/applestyleguide/#/apsgf72184e0)

### Abbreviations and acronyms

Abbreviations are a condensed form of a word. Acronyms are also abbreviations formed from the first letters of words in a phrase, but pronounced as if it were a word itself.


<div class="row" style="text-align:left;" markdown=1><img src="./assets/images/checkmark-graphic.png"  width="40"/></div>

 1. Spell-out in first instance of use in a document or topic in modular content. Include the abbreviation or acronym in parentheses following the spelled-out term.<br>
 2. Capitalize the spelled-out version if its a proper noun or is conventionally capitalized.<br>
 3. Use sparingly, except in tables and graphics.<br>
 4. If needed due to space constraints, use in a heading or title, and then spell out in the first paragraph. However, preferred choice is to spell out in the heading or title without the abbrevation in parentheses. Example: Device updates for full service restaurant.<br>
 5. Use a lowercase **s** to make abbreviations plural or possessive case. Example: three APIs; the CEO's blog.<br>
 
<div class="row" style="text-align:left;" markdown=1><img src="./assets/images/red-x-graphic.png"  width="40"/></div>
 1. Don't spell out abbreviations familiar to your audience even in the first instance, example: USB, FAQ, and URL.<br>
 2. Don't use periods with acronyms or initialisms, example: C.E.O. or A.T.M.<br>
 3. Don't abbreviate **Drive** or **Lane** in addresses. You can abbreviate—Ave., Blvd., Cir., Ct., Pkwy., Rd., Sq., St., Terr.<br>

[Back to top](#writing-standards)

_Good to know_:

Don't spell out the term if the acronym is listed in [The American Heritage Dictionary](https://ahdictionary.com/)

### Active and passive voice

 1. Use the active voice with an implied you to clarify who is performing the action.
 2. Active voice is direct and easier to translate, and uses fewer words. Fewer words mean a lower error rate and also a lower translation price.

|                                     Active voice                                    |                                       Passive voice                                      |
|:-----------------------------------------------------------------------------------|:----------------------------------------------------------------------------------------|
| The team completed the project on time.                                             | The project was completed on time by the team.                                           |
| Fiserv assigns the merchant_id parameter to uniquely identify the merchant account. | The merchant_id parameter is assigned by Fiserv to uniquely identify a merchant account. |

[Back to top](#writing-standards)

#### Rules for active and passive voice

Active voice sentence = actor + verb + target
Passive voice sentence = target + verb + actor

Passive sentences usually have:

 * A form of the verb _to be_, example: are, was, were, could be.
 * The word - by.
 * A past participle, generally with _ed_ on the end. 

Sometimes it is acceptable to use the passive voice when:

 * It is not important who performed the action.
 * You want to stress the action instead of the need to perform the action.

Example:

 * Dev Kits can be ordered from [fiservdevkit.com](http://cloverdevkit.com/).

 * Track your app's performance by monitoring installs and revenue

### Articles

<div class="row" style="text-align:left;" markdown=1><img src="./assets/images/checkmark-graphic.png"  width="40"/></div>

1. Use __an__ when the abbreviation or acronym has a vowel sound.

Examples:

ef-AS; ef-i - an FI can opt out of AUS; an FAQ; es-ql - an SQL query; an HTML file; an hour
fid (as pronounced) - enter a FIID in the field; a URL

<div class="row" style="text-align:left;" markdown=1><img src="./assets/images/red-x-graphic.png"  width="40"/></div>

2. Don't use an article (a, an, the) at the start of a bulleted list or a field description. This helps to create parallel structure in sentences.

|                                                                                                                                                                                           ![thumbs up](assets/images/thumbs-up.png)                                                                                                                                                                    |                                                                                                                                                                                        ![thumbs down](assets/images/thumbs-down.png)                                                                                                                                                                                         |
|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|**Solutions on the Fiserv platform**<br><br>The Fiserv platform provides:<br><br> * Cloud-based point of sale (POS)....<br> * Android-based POS devices.<br> * Android-based remote services (AIDL), content providers, and broadcasts through the Fiserv Services APK.<br> * Standard standard set of Android intents ...<br> * App Market for developers to publish their applications.</p>|**Solutions on the Fiserv platform**<br><br> * A cloud-based point of sale service and REST API<br> * Android-based point of sale devices<br> * Android-based remote services (AIDL), content providers, and broadcasts via the Fiserv Services APK.<br> * A standard set of Android intents that Fiserv and third-party applications can implement<br> * An App Market for developers to publish their applications. |
| * **Merchant Name**—Name of the merchant that displays on your dashboard and Dev Kits associated with the account.<br> * **Country**—Country where the merchant operates.<br> * **ZIP/Postal/PIN code**—Postal code for the merchant.                                                                                                                                  | * **Merchant Name**—The name of the merchant, which appears in your dashboard and on DevKit's tied to the account<br> * **Country**—The country where the merchant operates<br> * **ZIP/Postal/PIN code**—A valid postal code for the merchant                                                   |

[Back to top](#writing-standards)

### Bias-free and inclusive communication

<div class="row" style="text-align:left;" markdown=1><img src="./assets/images/checkmark-graphic.png"  width="40"/></div>

To avoid unnecessary usage of pronouns:

1.     Use words that do not unnecessarily distinguish genders.

Rewrite to use the second person (you).
Rewrite the sentence to have a plural noun and pronoun.
Use the or a instead of a pronoun, example: instead of his/her document; use—the document.
Remove the pronoun entirely.
Refer to a person's role, example: reader, employee, customer, or client.
Use person or individual (user).
If you can't write around the problem, use a plural pronoun (they, their, or them) to refer to a single person.

<div class="row" style="text-align:left;" markdown=1><img src="./assets/images/red-x-graphic.png"  width="40"/></div>

Don't use words that unnecessarily identify a person’s race, religion, physical status, social status, age, national origins, or gender.
Don't use constructions like he/she and s/he.

[Back to top](#writing-standards)

### Bullet list

Bullet lists present nonsequential items in easy-to-read, parallel format. Features of a bullet list are:

Contains at least two items.
Contains items of equal importance or those items that cannot be referred to using numbers or letters.
Contains fewer than three lines. If longer, rewrite. If all else fails, present additional information as an indent under the bullet.
<div class="row" style="text-align:left;" markdown=1><img src="./assets/images/red-x-graphic.png"  width="40"/></div>

Use a lead-in or introductory line, unless you introduce the list with a heading.
​Use parallel sentence construction.
Start each bullet item with a capital letter.
Period in bullet lists:
Phrase—no ending period, example: R=Card reissue status
Single word—no ending period, example: A=Active​
Complete sentences or two sentences—use ending period
5.     Use left justification only, not center justification.

[Back to top](#writing-standards)

 

### Capitalization

<div class="row" style="text-align:left;" markdown=1><img src="./assets/images/checkmark-graphic.png"  width="40"/></div> Our preferred style is sentence-case capitalization, that is, capitalize the first word and all proper nouns, such as product names.

Use sentence case in:
Document title, headings, and navigation.
Labels, callouts, field names, and other text in images and diagrams, even if they are in all upper case in the user interface (UI).
Items in all types of lists and tables.
Glossary definitions.
Use lowercase for glossary and index terms unless the term is a proper noun or requires capitalization.
Use camel case only in official names or when referring to code that uses camel case.
Date and time:
Date is always in all upper case.
Time is always in all lower case.
Examples for time and date entry formats:
Transmission Date & Time – MMDDhhmmss
Terms & Conditions Date/Time – YYMMDDhhmm
<div class="row" style="text-align:left;" markdown=1><img src="./assets/images/red-x-graphic.png"  width="40"/></div>

Don't capitalize words that are not proper nouns, branded names, or if their capitalization contradicts our style guidelines.
Don't use all-uppercase, except in official names, in abbreviations that are always written in all-caps, or when referring to code that uses all-caps.
Job titles, example: An adjustment specialist; Exception for Fiserv: Business Consultant
Don't capitalize any letters in a URL.

[Back to top](#writing-standards)

Good to know

Capitalize the first letter of the following:

Manuals and other documentation.
Product names.
Pop-ups, menu items, screens, application pages.
Proper nouns.
Teams and departments, example: The Documentation team, The UNIX team, The Finance department.
Headings and chapter titles.
Words following colons (:) and em dash (—)
References, example: See Chapter 7 (but not earlier in this chapter as that does not refer to a title.
Key names, example: Ctrl, Alt, Enter, Ctrl+P.
### Code formats

Font—Courier monospace font type is used in Windows command prompt, Mac terminal, every IDE, and most editors. The font type makes it easy to signify code and user input strings.
Example:



<div class="row" style="text-align:left;" markdown=1><img src="./assets/images/checkmark-graphic.png"  width="40"/></div>

 
Use `<code>` in HTML or the symbol below the tilde (~) symbol on your keyboard in Markdown to apply a monospace font and other styling to code in text, inline code, and user input. That symbol is also known as acute, backtick, left quote, open quote, back quote, or backquote. 
Use code blocks, `<pre>` or three back-ticks, for code samples or other blocks of code.
Use code font to mark up code, such as class names, method names, HTTP status codes, console output, and placeholders.
Use semantic HTML to control the style of text on a page. Example: Use code tags, <code> or `, instead of manually styling text with a monospace font.
See Basic syntax for Markdown.
See Extended syntax for Markdown.
<div class="row" style="text-align:left;" markdown=1><img src="./assets/images/red-x-graphic.png"  width="40"/></div>

 
Don't override or modify font styles inline.
Don't use code elements such as keywords and filenames as verbs or noun, or plural or possessive.
Attributes, commands, configuration parameters, expressions, tags—Inline monospaced font, gray-highlighted text is used for short code samples, file paths, system messages, and user inputs.
Example:
Open a web browser and navigate to http://localhost:8080.




Curly braces—Variable text is enclosed in braces. This text varies based on users and needs to be replaced with values unique to an environment. Example: Each merchant has a unique identifier, so it is indicated with a placeholder: {mId} or {merchantId}. When copying sample code that includes bracketed values, replace both the brackets and sample values with your data.
Angle brackets—Placeholder variables. Example: http://<hostname:port>; host=<your_hostname>
Square brackets—Use to indicate a parameter that is optional.
Example: In function(param1 [, param2]) - param1 is required and param2 is optional.

[Back to top](#writing-standards)

Markdown ready reckoner

Shortcuts and syntax for card descriptions, comments, checklist items, and your bio:

Formatting

Keyboard shortcuts

Markdown syntax

Bold text

Command/Ctrl + B

**text**

Italic text

Command/Ctrl + I

*text*

Strikethrough text

Command/Ctrl + Shift + S

~~text~~

Inline code

Command/Ctrl + Shift + M

`text`

Links

Command/Ctrl + K

[text](http://www.example.com)

Escaping Markdown

For literal markdown syntax, use a backslash '\' before the symbols

\*literal asterisks\*.







### Company names and logos

<div class="row" style="text-align:left;" markdown=1><img src="./assets/images/checkmark-graphic.png"  width="40"/></div>

1.     Follow the spelling and capitalization a company prefers. Rewrite sentences so that a lowercase letter does not begin a sentence.

2.     Check the trademark symbol that must be used with the first instance usage of the company name on a page or topic.

3.     When two or more companies occur in a sentence, write them alphabetically, example: American Express, Discovery, Mastercard, and Visa.

<div class="row" style="text-align:left;" markdown=1><img src="./assets/images/red-x-graphic.png"  width="40"/></div>

1.     Don't use symbols, such as exclamation marks, plus signs or asterisks, that form contrived spellings or that are part of the logo.

2.     Don't place Fiserv in front of group or business unit names and locations.

3.     Don't use possessive case with company names.

[Back to top](#writing-standards)

 

### Content organization

1.     Start writing your document by developing the headings, and structuring them to your audience’s concerns. This helps to reveal major groupings of information. See also: Headings.

2.     Put information in a logical order.

3.     Write short sections that make it easier to understand information.

1.     Use informative headings, as a roadmap to your document.

2.     Use ordered and unordered lists.

3.     Use tables to make complex material easier to understand, specially, if, then, else, or conditions and exceptions statements. If-then tables that organize the material by a situation and the consequence. Tables generally use fewer words than a textual explanation.

4.     Use visuals—images, diagrams, and flowcharts.

5.     Precede tables and visuals with explanatory text, example:

1.     The following diagram illustrates the standard two-phase distributed search process.

2.     The following image displays an example of the Uploaded Apps page.

6.     Be concise—leave out unnecessary words.

4.     Write general information first, with specialized information, or exceptions to the general information later.

5.     Similarly, in task-based writing, first describe the location, and then the action, example: In the Login field, enter your user ID.

6.     Place terms and definitions or glossary at the end, and list the entries alphabetically.

7.     Topic sentence provides a transition from one paragraph to another. Use strong topic sentences that brief the concept discussed in the paragraph.

8.     Use examples to help your readers understand your points. Set apart the test with—example: or Example: or such as. 

9.     Minimize cross-references as they distract from the content flow:

1.     Review material to remove unnecessary and cluttering cross-references.

2.     If the cross-reference text is brief, eliminate the cross-reference by including the text in the section.

3.     If the text is elaborate, you can cross-reference.

4.     If possible, design the content to include cross-references at the bottom on the page or end of the text, instead of in the middle of the running text.

5.     See also: Links.

Writing factual, direct statements to help a reader understand why an option is a good idea and whether it applies to them.
![thumbs up](assets/images/thumbs-up.png)

![thumbs down](assets/images/thumbs-down.png)

To minimize system impact, perform this action outside of normal business hours.

It is recommended to perform this action outside of normal business hours.

Mask specific values in images to hide sensitive information. 

We recommend concealing specific values in images.

Take the time to learn which indexes contain your data, the source and source type of your data.

 Fiserv recommends that you take the time to learn which indexes contain your data, the sources of your data, and the source type of that data.

[Back to top](#writing-standards)

Good to remember

Headings—Descriptive, informative, and concise.
Paragraphs and list items—Begin with identifiable concepts as early as possible.
Examples—Use for the most common use cases, but not for everything.
Linear and cumulative—Aim for the reader to follow your documentation, linearly, from start to finish. However, this is not always possible. Use cumulative ordering to increase retrievability, such as, examples and tutorials followed by alphabetic concepts.
Comprehensive—Cover one concept or topic in totality so that all questions are answered in that context.
Structure—Organize top-down, beginning with an overview, and gradually adding details.
Tables—Keep tables as simple as possible. Complicated tables that contain lists or merged cells are difficult to navigate using a screen reader. 
Links—Include  words which describe the link itself, and never phrases like click here or this page.
9.     Visuals—Use well-designed templates, diagrams with proper legends, and other visual tools to increase the effectiveness of the document, without going overboard with multiple styling.

10. Quality—Aim for correct spelling and grammar.

### Dashes em dash and en dash

Dashes—em dash

Dashes—en dash

Dashes—hyphen

<div class="row" style="text-align:left;" markdown=1><img src="./assets/images/checkmark-graphic.png"  width="40"/></div>**** Use em dash:

To offset and emphasize a statement; place on each side of a phrase embedded in a sentence.
Example: The information in your spreadsheet—numbers, formulas, and text—is stored in cells.
To offset text, as in a title or header, or definition, or to describe a value.
Example: Processor—EPOC Activity; A—First letter in the English alphabet.​
Before and after​—or—​ and —and—​ when describing multiple or alternate action paths
Before and after code formatted text with spaces, example:

Format:
First word following em dash is not capitalized when it occurs in a sentence.
If the em dash occurs in a title, or follows an introductory word/words in a list, or a proper noun then the first word after the em dash is capitalized.
Don't use spaces before and after in running text.
Use spaces before and after in code formatted text. See point 4.
<div class="row" style="text-align:left;" markdown=1><img src="./assets/images/checkmark-graphic.png"  width="40"/></div>Use en dash:

To indicate a range of numbers, such as inclusive values, dates, or pages. Example: 2015–2017
For a minus sign. Example: 12 – 3 = 9
To indicate negative numbers. Example: –79​
<div class="row" style="text-align:left;" markdown=1><img src="./assets/images/red-x-graphic.png"  width="40"/></div>

Don't use spaces before and after.

<div class="row" style="text-align:left;" markdown=1><img src="./assets/images/checkmark-graphic.png"  width="40"/></div>Use hyphens:

To join compound words. See Standard word list.
For a sequence of two hyphenated words with the same ending; known as: suspensive hyphenation. Example:
1.     We offered 1- and 2-year contracts.

2.     Both micro- and macroeconomic policies ...

3.     If a prefix ends in a vowel and the word that follows begins with the same vowel.
Example: pre-exist, auto-opt, co-owner
Exceptions: cooperate, coordinate.

4.     If the word that follows is capitalized - Mid-Release, Non-FI, non-XML.

5.     To join doubled prefixes.

6.     Often, you can replace a slash (/ ) with a hyphen to join equal or like terms, as in faculty-student ratio.  

<div class="row" style="text-align:left;" markdown=1><img src="./assets/images/red-x-graphic.png"  width="40"/></div>

Don't use spaces before and after.
2.     Don’t hyphenate compounds formed by an adverb ending in -ly followed by an adjective or participle, example:

highly regulated not highly-regulated market
rarely used not rarely-used services

[Back to top](#writing-standards)

Good to know

When to use

Typography

Hyphen
-

Joins two words

Narrowest type of dash

En dash
–

Joins two values or digits

In any font is the width of the letter N.

Em dash
—

Joins letters and sentences

In any font is the width of the letter M.

### Dates

Spell out dates in documents.

<div class="row" style="text-align:left;" markdown=1><img src="./assets/images/checkmark-graphic.png"  width="40"/></div>

1.     Dates in text: month day, year, as in July 31, 2022.
Example:

1.     The final report is due January 15, 2022—a month before the product goes live.

2.     We will recalibrate the system beginning on November 8, 2022.

3.     We’ll launch the new version in March 2023. 

2.     Use a numeral instead of ordinal numbers: June 1 or October 28. Always spell out the name of the month. 

<div class="row" style="text-align:left;" markdown=1><img src="./assets/images/red-x-graphic.png"  width="40"/></div>

1.     Don't use day month year, as in 31 July 2016.Upper case: MMDDYYYY; DDMM; MMDDYY

2.     Don't use ordinal numbers, such as June first or October twenty-eighth for dates. Exception: 1st, 2nd .... 15th are allowed in tables
Note: An ordinal number indicates the position or order of something in relation to other numbers, like, first, second, third, and so on.

[Back to top](#writing-standards)

 

### Error messages

<div class="row" style="text-align:left;" markdown=1><img src="./assets/images/checkmark-graphic.png"  width="40"/></div>

Focus on error recognition and recovery.
Clearly state the problem, the cause, and what the customer can do to remediate or recover.
Use complete sentences with end punctuation.
<div class="row" style="text-align:left;" markdown=1><img src="./assets/images/red-x-graphic.png"  width="40"/></div>Don't use please.

Original message

Rewritten message

Max number of concurrent searches reached.

The maximum number of concurrent searches is reached. Decrease the number of concurrent searches or increase search concurrency limits in limits.conf.

Unable to distribute to peer named xxxx at uri http://xxxx:8089 because peer has status = "Authentication Failed".

Unable to distribute to peer xxxx at http://xxxx:8089 because authentication failed. Make sure adequate system resources are available on the target server.

Max search jobs encountered.

The maximum number of search jobs is reached. To reduce the number of search jobs, go to Job Inspector, and delete unneeded jobs.

Could not load/save the object. May need to check user settings for roles and permissions. Details: An internal error has occurred.

The cloned table cannot be saved as it has the same name as the original. Rename the cloned table.

 

[Back to top](#writing-standards)

 

### Folder and file naming conventions

<div class="row" style="text-align:left;" markdown=1><img src="./assets/images/checkmark-graphic.png"  width="40"/></div>

1.     Length: Limit folder and file names to 25 characters. Less is more. A URL cannot be longer than 255 characters; as a best practice limit the folder hierarchy to 225 characters.

2.     Use hyphens, not underscores, to separate words, in a topic name/URL, example: query-data.html

3.     Make file and directory names lowercase.

4.     Use only standard ASCII alphanumeric characters in file and directory names.

Camel case: Use the camel case to delimit words. Camel case, means in a word the first letter should be capital, example: TransactionData, or Transaction-Data.
<div class="row" style="text-align:left;" markdown=1><img src="./assets/images/red-x-graphic.png"  width="40"/></div> Don't use

Long file name with long file paths and URLs as they increase likelihood of error.
2.     Special characters in a file name. \ / : * ? " < > | [ ] & $

3.     Spaces in File and Folder names to delimit words. Spaces are frequently translated in a Web environment to be read as "%20".

4.     Articles – "a", "an", "the"

5.     Underscores/double underscores, double hyphens - _ __ --

6.     Period (.) at the start or end

7.     Initials, abbreviations and codes that are not commonly understood. 

[Back to top](#writing-standards)

 

### Headings and subheadings

1.     Limit heading levels to three or fewer. Any more levels may indicate your content is complex. This also makes it difficult for your audience to keep track of the document structure.

2.     API reference headings are verbs that indicate the CRUD action.

3.     Use sentence case.

4.     Preferred—spell out in the heading or title without the abbrevation in parentheses, example: Device updates for full service restaurant, unless there is a space constraint.

5.     Use informative, specific, and inclusive text.

6.     Use task-based text, that is, mention the action to perform, not the name of the page or window or option. Introductory sentence should not repeat the task-based heading.
Example:
Heading—Calculate the estimate payoff
Introductory sentence—Use the Estimate Payoff option to calculate the … when or why

7.     Try and limit the number of words in a heading to 6; and in subheadings 6-8 words.

8.     Do not use gerunds at any heading level.

Topic titles and Task-based procedure headings - All levels

Concept topic headings -  All levels

Use active voice, verb phrase:

Get started
Set up your first online order
Set up online orders
Exception: Online Ordering is a Fiserv-branded service
Expand merchant business
Export merchant data
Join our community
Integrate with Fiserv Android SDK
Manage your apps
Monetize your app
Set up your sandbox
Set up your app billing
Use nouns and simple noun phrases:

Android APKs
API Errors
Before you begin
Prerequisites
Fiserv architecture
Fiserv environments
Fiserv Hardware SDKs
Inventory
Merchants
Merchant accounts
Merchant data
OAuth 2.0
Orders
Pricing and distribution (if that is what the DP calls it)
Price tiers or Pricing tiers (depends on what the DP calls it)

[Back to top](#writing-standards)

Example

 





### Images

Use images to supplement written information. If possible, use tables and lists, to convey the information instead of images, specially in beta or unstable UI applications. A well-designed UI doesn't need an accompanying screenshot in the documentation.

<div class="row" style="text-align:left;" markdown=1><img src="./assets/images/checkmark-graphic.png"  width="40"/></div>

Capture a screen shot using the light theme with your screen zoomed to 100%.
2.     Introduce each image with a full sentence that describes its contents.

Provide alt text that adequately summarizes the intent of each image. Alt text is a  concise description of the image that can replace the image when it isn't visible.
Use SVG file type instead of PNG, if available. SVGs stay sharp when you zoom in on the image.
5.     Use inline image in a sentence to label a UI element, such as a toolbar icon or a button.

In Readme, use Smart Fit: 
<div class="row" style="text-align:left;" markdown=1><img src="./assets/images/red-x-graphic.png"  width="40"/></div>

Don't use actual numbers, customer or merchant data, or PII in images. See Inclusive names and secure data.
Don't present new information in images; always provide an equivalent text explanation with the image.
Don't repeat images unless absolutely necessary.
Don't use images of text, code samples, or terminal output. Use actual text.

[Back to top](#writing-standards)

Best practices for alt text for images

In alt text:

Use sentence case. 
Include punctuation. 
Use consistent alt text for repeated instances of an image, such as, icons.
Use full sentences in 155 characters or less.
If you need more than 155 characters,:
Include a brief summary of the image in the altattribute.
Include the longdesc attribute to link to a more extensive description of the image. The longdesc attribute value should be a link, not text.
### Inclusive names and secure data

In images and examples:

<div class="row" style="text-align:left;" markdown=1><img src="./assets/images/checkmark-graphic.png"  width="40"/></div>

1.     Use names sensitive to culture, religious affiliation, holidays, traditions, politics, and business. Make sure that the name you create reflects the wide range of names used around the world.

2.     Provide imaginary examples or use placeholders, like USER_ID or EMAIL_ADDRESS.

3.     Use test card numbers.

<div class="row" style="text-align:left;" markdown=1><img src="./assets/images/red-x-graphic.png"  width="40"/></div>

1.     Don't reveal personally identifiable information (PII), such as domain names, email addresses, phone numbers, people's names, project names, or credit card numbers.

2.     Don't use:

1.     Fictional or movie characters, your own name, or the name of friends or family members

2.     Actual domain names

3.     Actual merchant names

4.     Actual addresses

5.     Actual card, account, or PIN numbers

6.     Actual phone numbers

7.     IP addresses

[Back to top](#writing-standards)

 

Recommended replacements for PII

 

First name

​Alex, Amal, Chris, Dana, Hao, Kai, Kim, Kiran, Lee, Nur, Sasha, Taylor, Wei, Yuri

Last name

Smith, Public, Doe, Martin, Patel, Garcia, Paulo, Zhang

Domain name

example.com
example.org
example.net
example.io

For more information, see Reserved domains.

Email addresses

.... example.com
alex@example.com
developers@example.com
yuri.smith@example.com
test.merchant@example.com
info@example.com

Company names

Example Organization
Enterprise Example Organization
Startup Example Organization

US phone numbers

From (800) 555-0100 through (800) 555-0199

Australia phone number

+61-2-5550-9988

Int'l phone numbers

Include the country and area codes. Example:
+1&nbsp;415&nbsp;555&nbsp;0132

IPv4 addresses

192.0.2.1
198.51.100.1
203.0.113.1
IPv4 address ranges

192.0.2.0/24
198.51.100.0/24
203.0.113.0/24
IPv6 addresses

2001:db8::
2001:db8:ffff:ffff:ffff
2001:db8:1:1:1:1:1:1
2001:db8:2:2:2:2:2:2
IPv6 address ranges

2001:db8::/32
Addresses

1800 Amphibious Blvd.
Mountain View, CA 94045
Avenida da Pastelaria, 1903
Lisbon, 1229-076
8 Rue du Nom Fictif
341 Paris
Tokens

GitHub fake tokens

### Informal tone

Informal tone is used mostly in eLearnings, announcements, blogs, and FAQ. Procedures and technical concepts or references should be formal and straight to the point. Lead-in lines or topic sentences may use some informal tone in the introduction.

1.     Write as you talk is a common rule of writing that is readable; however don't use slangs or jargons; or too casual a tone. 

Use contractions—Let's, isn't, don't, and can't—but with discretion, and where they sound natural.
Be cautious. When in doubt, use a formal tone.

[Back to top](#writing-standards)

 

### Information classification

Using proper classification ensures that all document sharing is handled efficiently and securely to protect against data security threats.



Set up Document Properties, example: in Microsoft Word, Excel, PowerPoint, Visio, ​and so on, as follows:​

​Open a document.
Click File > Info.
Select the drop-down arrow next to Properties, and then click Advanced Properties.
Select the Custom tab.
Do one of the following:
Add—​​Enter Confidentiality in the ​Name field, enter appropriate document classification in the Value field, and click Add.
Modify—​Click Confidentiality in the Properties field, enter appropriate document classification in the Value field, and click Modify.
Click OK.​

[Back to top](#writing-standards)

Best practices for data handling

Data Classification and Handling Standard

​Contact:​
Fiserv Data Loss Prevention <dlpinfo@fiserv.com>
Cyber Risk Manager (CRM) - For additional questions regarding classifications.

See Developer Studio copyright on GitHub for Fiserv.

### Links Cross references and hyperlinks

<div class="row" style="text-align:left;" markdown=1><img src="./assets/images/checkmark-graphic.png"  width="40"/></div>

Format: Regular text: Fiserv font (#228800)
Link judiciously to supporting material or additional information.
Use short descriptive text that provides context to the material to which you are linking. The phrases - Click Here, Read More, Find It, Buy Now, or any other, do not tell the user nothing about the content of the link.
·       Keep link text concise - Maximum length = 100 characters; Do not link whole paragraphs or sentences.

·       Underline link text - this is the only element that should be underlined on a page.

Precede the link text with reference words—For more information...; See...; Download...; Learn about...; in this document (when the link is on the same page).
Example:
For more information about authentication and authorization, see Using OAuth 2.0 to access Google APIs.
See Coding guidelines.
Download the Product design cheatsheet.
Learn what's new in Android Wear 2.0.
In this document, see links to pages on the same server.
Include the abbreviation in the link text.
Example: Google Kubernetes Engine (GKE)
Include description of the code element in the link text. 
Example: To create an instance with a custom hostname, run the gcloud instances create command with the --hostname flag.

Put punctuation outside of the link tags.
Use cross-references to guide readers to related information. For same-server links, use site-root-relative URLs.
·       When linking to pages on a different server, if the server that you're linking supports HTTPS, start the URL with https. If the server doesn't support HTTPS, start the URL with http.

·       Use unique pairs of URLs and link texts in your content.

o   Do not use same text to link to two different URLs. Example: Using OAuth 2.0 links to Using OAuth 2.0 topic and also the Obtaining an OAuth token topic.

o   Do not use different text to link to the same URL. Example: Using OAuth2.0 and Obtaining an OAuth token link to the same OAuth topic.

Be careful with using images as links. In an image:
ALT attribute acts as the link text.
ALT attribute must describe the image and it must tell the user what activating the link will do. 
<div class="row" style="text-align:left;" markdown=1><img src="./assets/images/red-x-graphic.png"  width="40"/></div>

Don't use phrases such as this document, this article, or click here.
Don't use a URL/web address as link text. Screen readers will read each character (w-w-w-dot-h-t-t-p-colon...). Use the page title or a description of the page. Exceptions: To indicate the actual text, example: www.eu.docs.fiserv.com; API reference or sandbox link.
Don't force links to open in a new tab or window. Let the reader decide how to open links.
Don't provide links to the same document in a given page; provide links to sections, if needed. This is backed by research by the Nielsen Norman Group.

[Back to top](#writing-standards)

Best practices for links

1. Add a <section> element with an id attribute. Don't use <a name>. Use lowercase for id values, and put hyphens between words.

<section id="introduction-to-everything"> <h2>Introduction to everything</h2> ... </section>



2. Rarely, if a link needs to open in a new tab or window, let the reader know that the link opens differently than expected.

<a href="/style/accessibility" target="_blank">Accessible content (opens in a new tab)</a>


3. When linking to another page on the same server, use a site-root-relative URL starting with /.



4. If the URL has a locale indicator, remove it, and then test the link.
Example: Remove en in the following link:

https://en.wikipedia.org/wiki/Operating-system-level_virtualization

5. Use a site-root-relative URL (starting with "/") when linking an image.

Insert the URL in the src attribute of your <img> element:

<img



  src="/shared/images/arrow-24.png"



  alt="Alt text description of arrow image."



/>

### Line Breaks

Split up long lines of code with line breaks so that the lines of code fit within the page width and don't extend off the screen. When deciding where to break a search string, prioritize the break based on the following list:

Before a pipe |
At a space 
Before and after an open parenthesis or bracket ( ) [ ]
Before or after an equal sign = 
Before or after any equation symbol, such as *, /, +, >, <, or - 7.
After a dot, such as in a URL
Example:



[Back to top](#writing-standards)

 

### Mouse terminology

Term

Usage

mouse pointer/cursor

Use pointer.
If needed, use cursor only for a technical audience or to describe the point on the screen to insert a text or graphic.   

mouse button

Use to indicate the left mouse button. Use right mouse button, only if it is needed, example: Click the right mouse button to display the shortcut menu.

drag

Use drag , not click and drag or drag-and-drop for moving a file from one place to another.
Drag-and-drop is used as an adjective. Example: Drag the folder to the desktop. Moving the folder is a drag-and-drop operation.

mouse over or move the mouse pointer to

Do not use. Use hover over.

[Back to top](#writing-standards)

 

### Notices Notes, tips, warning, and important

Use notes and other notices sparingly. They lose effectiveness if used too often. Avoid using an Important notice or Note immediately before or after a Note, Warning, or another Important notice, or immediately after a text head. 

·       Important is information that the user must have. If they do not use it, the procedure will fail. 

·       Note is for information that is useful or related to the topic but can be skipped by the reader. Most notes should be a continuation of body text. A note should be no more than 4 lines.

·       Caution is a warning.

[Back to top](#writing-standards)

 

### Numbers

Numbered lists are used to list a series of items or steps in order of priority, or in the order/sequence in which a set of steps have to be performed. See also Bullets.

[Back to top](#writing-standards)

 

### Numbered or ordered lists

1. Spelling out numbers in paragraphs

1.     Spell out numbers one through nine if a paragraph has only numbers nine and below. 

2.     If you have number 10 and also numbers below 10, then use the digits for all numbers.

3.     If a sentence has a mixture of values 1–9 and greater than 9, use numbers for all the values. Example: This procedure supports sections 1, 6, 10, and 15 of the policy.Exceptions: units of measurement, time, input. Example:

1.     In text—One institution, four sandwiches, nine skateboards.

2.     Units of measurement—1 inch; 7 feet; 4pm; 5-digit; Enter 6 in the field.

2. Using numeric in tables

1.     Always use numbers in tables, even for one through nine—In spec or tables: 1 institution, 4 sandwiches, 9 skateboards. 

2.     Use numbers when the numbers are 10 or above.

3. If a number starts a sentence, spell it out—in body/paragraph text. If it is in a table, use the number.
Example:

·       In tables: 8-digit institution number.

·       In text: Ten APIs are available for download.

4. Use numbers with units of measure—including dates, time, age, page numbers, percentages, money, proportion, length, weight, volume, and velocity. Example:

·       4 days

·       8-character terminal identifier

5. If you have two numbers in one sentence—Try rewriting the sentence to separate the consecutive numbers (preferred). If it does not work then use text for the first number. Example:

Submit up to six files, each of 100 bytes.
Submit up to 10 files, each of 100 bytes.

[Back to top](#writing-standards)

 

### Parallel structure

Parallelism is a convention of sentence construction. It is indicated by the same grammatical form and applies to verbs, nouns, adjectives, and every other part of a sentence. In technical documentation, parallelism provides uniformity in bullet lists and step-by-step instructions—namely, putting the action-word first, followed by the steps.

![thumbs up](assets/images/thumbs-up.png)

![thumbs down](assets/images/thumbs-down.png)

Enter client ID.
Select View EJ Data.
Enter a terminal ID.
Select View Balance.
Enter the client ID.
Make sure View EJ Data is selected.
Terminal ID must be entered.
Select View Balance.

[Back to top](#writing-standards)

 

### Parentheses

Parentheses are less emphatic than em dashes and more emphatic than commas.  In general, parentheses are used to insert material into a sentence, such as explanations, references, citations, examples, or ideas that are not part of the main sentence.

<div class="row" style="text-align:left;" markdown=1><img src="./assets/images/checkmark-graphic.png"  width="40"/></div>

Use parentheses ( ) to clarify such as, adding examples or relaying a nuance or a small bit of clarifying data that are often subordinate to the main point.
Use em dashes (opt+shft -) to set an important phrase apart in a way that emphasizes versus subordinating it—like a wink or a nod to the reader. They are a great substitute for a semicolon—a way to make two points at once.
Use brackets [ ] to set off comments, corrections, mathematical expressions, and incidental or explanatory material. Example: The quoted price [$3,750] exceeds the budgeted amount.
<div class="row" style="text-align:left;" markdown=1><img src="./assets/images/red-x-graphic.png"  width="40"/></div>Don't to use parentheses, especially for complete sentences. Rewrite as a separate sentence, as a note, or use commas. For a set of words or phrases, set off with em dashes.

[Back to top](#writing-standards)

 

### Person

<div class="row" style="text-align:left;" markdown=1><img src="./assets/images/checkmark-graphic.png"  width="40"/></div>

When you write from the point of view of the Fiserv brand, use the first person plural (we). This helps to use lesser words and avoid passive voice.
Example: We built Fiserv Dining with the input of restaurants like yours. That makes our POS custom-built for your restaurant
To communicate with/to our merchants, use the second person (plural or singular).
Example: Our POS is custom-built for your restaurant. Your menu. Your staff. Your floor plan.
To write about our products and services, use the 3rd person singular (it).
Example: Fiserv Dining makes taking, coursing, and updating orders fast, simple, and accurate.
4.     State in the beginning of the document who the user is and use you for the user.

5.     In a question-and-answer format, assume that the user is asking the questions. Use I in the questions to refer to the user. Use we in the responses to represent your agency.

![thumbs up](assets/images/thumbs-up.png)

![thumbs down](assets/images/thumbs-down.png)

Submission of applications.

How do I apply? 

<div class="row" style="text-align:left;" markdown=1><img src="./assets/images/red-x-graphic.png"  width="40"/></div>Don't mix the grammatical person within the same sentence.

[Back to top](#writing-standards)

Good to know

First person (I, we)—My favorite restaurant uses Fiserv. I eat there every weekend.
Second person (you)—When you’re ready to get a new POS, you might want to consider Fiserv.
Third person (he, she, it, they)—Fiserv products can make running a business more efficient.
### Prepositions

When documenting the UI, use the following prepositions.

Preposition

UI element

Recommended

in

dialogs

fields

lists

menus

panes

windows

In the Alert dialog, click OK.

In the Name field, enter wsfc-1.

In the Item list, select Desktop.

In the File menu, click Tools.

In the Metrics pane, click New.

In the Task window, click Start.

In the Terminal, run the following command:

on

pages

tabs

toolbars

On the Create an instance page, click Add.

On the Edit tab, click Save.

On the Dashboard toolbar, click Edit.

[Back to top](#writing-standards)

 

### Punctuation

Punctuation

Usage

General rules

Limit the usage of exclamation mark (!) and double (" ") (') or single quotations, unless referring to an actual quotation.
Place periods and commas within the quotation marks.
Place question marks and exclamation points inside the quotation marks if they are part of the quote and outside the quotation marks if they apply to the entire sentence.
Place semicolons and colons outside the quotation marks.
·       Use only one space after any punctuation marks within a sentence.

Colon

Colon indicates what follows the punctuation is to explain, illustrate, or add details.
Use to set off a list or series, such as before the word example: or do one of the following: 
Capitalize the first word following a colon. Use commas or colons before direct, complete quotations.
Comma

Use commas in numbers of four or more digits.
Set off the clause or phrase with a comma when a sentence begins with—when, if, during, although, because, before, after, according to, since, or similar words.
Use a comma between two independent clauses connected by conjunctions—and, or, but, for, nor 
Serial or oxford comma—In a series of three or more items, use a comma before the final and or or.
Example:
The software automatically generates reports, letters, and customer statements.
This training covers adding, modifying, and deleting client information.
Semi-colon

Avoid. Try to rewrite the sentence by splitting it up or breaking up the series of clauses or phrases into a list. Semi-colons are used instead of commas when a sentence has a series of long clauses.

Periods

·       Place the period inside the closing parentheses, if the entire sentence is enclosed by parentheses.

Place the period at the end of the closing parentheses, when it encloses a partial sentence towards the end. If possible, use an em dash to eliminate the parentheses. 

[Back to top](#writing-standards)

 

### REST API formats

Formatting conventions for many REST API elements, like endpoints, methods, parameters, requests and responses, and so on. For more details, including command line formats, see the Formatting Guidelines document.

Element

Format

Capitalization rules - in all instances

API names, methods, endpoints - always use the actual upper/lower letter casing even in headings or any other references.
Example: dateFunded endpoint has lower case d, so in Titles, headings, or field name columns use the actual camel case. This prevents ambiguity and conforms with the rule of consistency.

API names

No formatting. Use the actual upper/lower letter casing in all instances - text, headings, and so on.

Endpoints, Class, Objects, Methods, Parameters

Regular font in running text.
Inline Courier font in code samples with gray-highlight.
Use the actual upper/lower letter casing in all instances - text, headings, and so on.

HTTP methods

All upper case letters, inline Courier font, depending on use

REST API methods

No formatting; Request name is in all upper case letters.

JSON bodies

Courier font block

REST API requests and responses

Courier font block

REST response body

Courier font block

Request parameters

Inline Courier font

Returned REST response value

Inline Courier font

[Back to top](#writing-standards)

 

### Spellings

<div class="row" style="text-align:left;" markdown=1><img src="./assets/images/checkmark-graphic.png"  width="40"/></div>

Use American spellings in all text and documents, irrespective of the region, such as US, EMEA, Canada, and so on.
Set English (US) as the default language of your computer and applications.
In MS Word, select Review > Language > English (US).


In Google Docs, select Review > Language > English (US).


For differences in American and British grammar, go to:
Preply.com
Learn English by British Council
ProWritingAid
Eleven Writing
ProofReadingPal
Writing Skills - PDF
In US English, double quotes are used, while UK English uses single quote marks.
<div class="row" style="text-align:left;" markdown=1><img src="./assets/images/red-x-graphic.png"  width="40"/></div>Do not use English (UK) spellings.

[Back to top](#writing-standards)

Spelling variations - US versus UK English

Rule

BRITISH

US

-our vs -or

Most words ending in ‘-our’ in UK English end in ‘-or’ in US English, xcept for contour, velour, paramour, and troubadour

colour

color, flavor, honor, neighbor, rumor, labor, humor

-ise vs -ize
Words ending in ‘-ise’. US English changes most of these to ‘-ize’ and ‘-yse’

organize or organise

organize, recognize, analyze

-re vs -er

centre

center, kilometer, theater, caliber, fiber

-ll  vs l
In UK English, ‘L’ is doubled in verbs ending in a vowel plus ‘L’. In US English, the ‘L’ is not doubled.

travelled, travelling

traveled, traveling

-ce vs -se

Both UK and US English use ‘advice’ as a noun and ‘advise’ as a verb, but US English has abandoned the ‘licence’/‘license’ and ‘practice’/‘practise’ distinction and uses ‘practice’ and ‘license’ for both meanings.

Americans use ‘defense’ and ‘offense’, while Brits write ‘defence’ and ‘offence’. ‘Defensive’ and ‘offensive’ always have an ‘s’. Hence, some nouns that end with ‘ence’ in British English are spelled ‘ense in American English.

licence

license

-ogue vs og or ogue

analogue, catalogue, dialogue

analog, catalog, dialog

-ae, -oe vs -e
Words written with ‘ae’/‘oe’ in UK English have a single ‘e’ in US English

anaemia, paediatric

anemia, pediatric

For details, go to: Oxford International English.

### Present tense

<div class="row" style="text-align:left;" markdown=1><img src="./assets/images/checkmark-graphic.png"  width="40"/></div>Use present tense rather than future tense.

The future says that an action will happen at some point in the future, raising the question - when?
The present tense implies immediacy.
![thumbs up](assets/images/thumbs-up.png)

![thumbs down](assets/images/thumbs-down.png)(avoid)

A predefined set of columns displays.

Predefined set of columns will display.

The transaction contains an attempts AAV.

The transaction will contain an attempts AAV. 

<div class="row" style="text-align:left;" markdown=1><img src="./assets/images/red-x-graphic.png"  width="40"/></div>Avoid using will would, shall, and should.

Exception: When an action really does take place in the discernible future.
Example:

·       In this training, we will learn. 

·       We will discuss the other tabs later in this lesson.

[Back to top](#writing-standards)

 

### Text formats

<div class="row" style="text-align:left;" markdown=1><img src="./assets/images/red-x-graphic.png"  width="40"/></div>

**Bold**

* Use for field labels, button names, menus, and other user interface elements.

Example:

  *  On the home screen, tap Orders.
  *  Click the Inventory tab to add modifiers.
  *  Select the Approved checkbox.
  *  Select Yes.
* Values when followed by a definition.

Example:

Values:

  *  A = Active
  * C = Closed
  * R = Rejected

**Italics**—Use italics formatting, <i> or _
1.  Variable text, such as folder names or ID values that are different for each user.

2.  Text references to exact headings and titles unless they're part of a link.

3.  Mathematical variables and version variables. Example: x + y = 3, version 1.4.x.

4.  Words that are offset from the meaning of your sentence. Example: Search for Query tables on the Microsoft website.

5.  Error messages as they display on the UI. Example: Error message—Invalid input value—indicates the value you entered is unable to generate a certificate.

<div class="row" style="text-align:left;" markdown=1><img src="./assets/images/red-x-graphic.png"  width="40"/></div>

1.  Avoid unnecessary font formatting. Use regular text and bold only in text.

2.  Don't use underlines.

3.     Don't force line breaks or hard returns within sentences and paragraphs. Line breaks may not work well in resized windows or with enlarged text.

4.     Avoid use of exclamation marks, quotation marks, and question marks, and semicolons.

5.     For more details, including command line formats, see the Formatting Guidelines document.

[Back to top](#writing-standards)

Quick reference


|                                                  Element                                                 |                                                                                        Format                                                                                        |
|:--------------------------------------------------------------------------------------------------------|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Button names icons & keys                                                                                | Bold. Select Save. (Preferred usage) Press Ctrl + P. Tap OK.                                                                                                                         |
| Links and tab names                                                                                      | Bold only in an action sentence. Select the T&C link. Select the Home tab.                                                                                                           |
| Value entered in a field, selected from a list, or option, and the checkbox name                         | Bold. Select A=Active from the Status drop-down list. Select Yes from the Permit option. Select the Activate checkbox. Select the Date and Time options—Date range or Specific Date. |
| Screen or page name Pop-up; dialog Menu or submenu names                                                 | Regular.                                                                                                                                                                             |
| Fields, drop-down list name                                                                              | Regular.                                                                                                                                                                             |
| Messages that display on the screen. Values that display in fields. Exact book names and chapter titles. | Italics The field displays N/A. A message appears—Your password is changed. See Getting Started for more information.                                                                |

### Tooltips

Tooltips identify or add supplemental information to a UI element, such as icons or fields.

<div class="row" style="text-align:left;" markdown=1><img src="./assets/images/checkmark-graphic.png"  width="40"/></div>When writing a tooltip:

1.     Be short and concise—one word to a couple short sentences.

2.     Use sentence-style capitalization.

3.     Use a period to punctuate full sentences, unless it is one word, a short phrase, or the name of a tool or icon.

4.     Use present tense.

<div class="row" style="text-align:left;" markdown=1><img src="./assets/images/red-x-graphic.png"  width="40"/></div>Don't use please.

[Back to top](#writing-standards)

 

### Verb forms in reference documentation

Verbs tell your audience what to do. Make sure they know who does what. 

1.     Use singular nouns and verbs.

2.     Use present tense - the simplest and strongest form of a verb. 

| ![thumbs up](assets/images/thumbs-up.png)                                            | ![thumbs down](assets/images/thumbs-down.png)                               | \| |
|--------------------------------------------------------------------------------------|-----------------------------------------------------------------------------|----|
| Developers must set up their sandbox environment with unique user IDs and passwords. | You must set up the sandbox environment with a unique user ID and password. |    |

3.     In reference documentation, you tell the developers what the method does (gets, lists, creates, searches), rather than what they should do (get, list, create, search).

| ![thumbs up](assets/images/thumbs-up.png)                    | ![thumbs down](assets/images/thumbs-down.png)               |
|--------------------------------------------------------------|-------------------------------------------------------------|
| tasks.insert: Creates a new task on the specified task list. | tasks.insert: Create a new task on the specified task list. |

4.     In a specification, for API implementation, you tell the developers what their implementation of the method should do, so use the verb form without the -s (create a new task)

[Back to top](#writing-standards)

### Videos and accessibility

Use the following guidelines for videos. For more information see, Video Style Guide.

<div class="row" style="text-align:left;" markdown=1><img src="./assets/images/checkmark-graphic.png"  width="40"/></div>

1.     Link to videos created by Fiserv and ideally no longer than 4 minutes in duration.

2.     Include your video in an appropriate HTML tag. Example: `<video>`, `<embed>`, `<iframe>`, or `<object>`.

3.     Always include captions and transcripts with videos.

4.     Synchronize captions with the video and include all dialogue and important sound effects.

5.     If your video covers important visual details, make sure to describe them in your voice over.

6.     Explore options of creating GIFs to show simple processes that can be conveyed in 5 seconds or less. You can use an animated GIF to supplement task information or paragraph text.

<div class="row" style="text-align:left;" markdown=1><img src="./assets/images/red-x-graphic.png"  width="40"/></div>

1.     Don't make viewing the video as a requirement to complete a task.

2.     Don't use actual numbers, customer or merchant data, or PII in images. See [Inclusive names and secure data](#inclusive-names-and-secure-data).

[Back to top](#writing-standards)

 

### Words and sentences

1.     Use words and terms consistently throughout your documents.

2.     Omit information that the audience doesn’t need to know. An SME may want to include technical information. Keep your focus on what the audience needs.

3.     Watch out for of, to, on, and other prepositions. They often mark phases you can reduce to one or two words.

4.     Express only one idea in each sentence. 

5.     Start with your main idea – don’t start with an exception.

6.     Keep subject, verb, and object close together.

 1.     Put conditionals such as only or always, and other modifiers next to the words they modify.

 2.     Put long conditions after the main clause.
7.     Write short paragraphs and include only one topic in each paragraph.

  1.     No more than 150 words in three to eight sentences.

  2.     Never longer than 250 words.

  3.     Occasional one sentence paragraph is okay.
 
8.     Use positive words and avoid double negatives. Watch out for these words when they appear after _not—unless, fail to, notwithstanding, except, other than, unlawful (un- words), disallowed (dis- words), terminate, void, insufficient,_ and so on. 
9.     Transition words or phrases tell the reader whether the paragraph expands on the paragraph before, contrasts with it, or takes a completely different direction. 

  1.     Pointing words—this, that, these, those, and the—refer directly to something already mentioned.

  2.     Explicit connectives—further, also, therefore— provide transitions between sentences and paragraphs can be overdone.
  3.     If needed, when sequencing ideas, in text—First, Second, Third, Finally.
10.     Choose clarity over conciseness, as necessary.

|                                                      ![thumbs up](assets/images/thumbs-up.png)                                                     |                                      ![thumbs down](assets/images/thumbs-down.png)                                     |
|:----------------------------------------------------------------------------------------------------------|:--------------------------------------------------------------------------|
| Submit a GET request.                                                                                      | Do a GET.                                                                  |
| Use the map_get() function to extract nested values from the attributes field.                             | The map_get() extracts nested values from attributes.                      |
| The auth header is included by default, unless the noAuth flag is set.                                     |  Auth header is included by default, unless noAuth is set.                 |
| If you use the start.ini file to define JVM arguments, add the javaagent argument after the --exec option. |  If you use start.ini to define JVM arguments, add javaagent after --exec. |
| From the command line, run the following command to start your app in develop mode: yarn run start.        | Run the following to start in dev mode: yarn run start.                    |                                                   |

<div class="row" style="text-align:left;" markdown=1><img src="./assets/images/red-x-graphic.png"  width="40"/></div>

1.     Avoid legal, foreign, and technical jargon.
2.     Don't use excess modifiers such as absolutely, actually, completely, really, quite, totally, and very.

3.     Avoid directional language - above, below.

4.     Don't use that and which interchangeably. That introduces an essential clause; which introduces a nonessential clause and is preceded by a comma.

5.     Don't use that for a person. Use—who.

[Back to top](#writing-standards)

Remove redundancy

|                                                                                                                                                                                    ![thumbs up](assets/images/thumbs-up.png)                                                                                                                                                                                    |                                                                                                                     ![thumbs down](assets/images/thumbs-down.png)                                                                                                                     |
|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ·       a number of<br> ·       a sufficient<br> ·       number of<br> ·       at this point in time<br> ·       is able to<br> ·       on a monthly basis<br> ·       on the ground that<br> ·       an amount of X<br> ·       be responsible for<br> ·       in order to<br> ·       no fewer than<br> ·       at present<br> ·       have been<br> ·       have the option to<br> ·       is able to<br> ·       if you want to<br> | ·       several, a few<br> ·       many<br> ·       enough<br> ·       now<br> ·       can<br> ·       monthly<br> ·       because<br> ·       X<br> ·       must<br> ·       to<br> ·       at least<br> ·       now; currently<br> ·       are<br> ·       can<br> ·       can<br> ·       optional |
