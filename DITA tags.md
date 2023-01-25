# COMMON
```
<conbody> (the body of the concept topic)
<p> (a paragraph)
<ul> (an unordered or bulleted list)
<ol> (an ordered or numbered list)
<sli> (simple list)
<li> (a list item inside a <ul> or <ol>)
<fig> (a figure, including an optional title)
<image> (a graphic inside a figure, or inline in text)
<section> (a subdivision in the topic, with an optional title)

<xref> (cross-references)
<related-links> (end of topic links)
	<link href="URL" format="html" scope="external">
	
conref to reference content
	<note conref="location.dita#topicid/whatduckslike"/>
```

# TABLES
```
<simpletable>
	<sthead> header row
	<strow> body row
	<stentry> simple table entry
<table>
	<title> title for the table
	<tgroup> columns specifications, header rows and body rows
	<colspec> column widths and identifying info
	<thead> table header rows
	<tbody> table body rows
	<row> single row
	<entry> data for table cell
```

# PROLOG ELEMENTS
<author> (the content author)
<critdates> (critical dates, such as <created> and <revised>)
<copyright> (copyright year <copyryear>, and copyright holder <copyrholder>)
<vrm> (product version, release, and modification information)

# STRICT TASK TOPIC
<taskbody> (the body of the task topic)
<steps> (the sequence of actions)
<step> (each individual action)
	<cmd> (the action the user takes; this is a required element in a <step>)
	<info> (additional information about the step)
	<stepresult> (what happens after performing an action)
	<stepxmp> (an example of how to do the step)
<example> (an example of how to do the entire task)

# REFERENCE TOPIC
<refbody> (the body of the reference topic)
<section> (a subdivision in the reference topic, with an optional title)
<table> (a table)
<fig> (a figure, including an optional title)
<properties> (a list of properies)
<refsyn> (a syntax diagram)

# GLOSSARY TOPIC
<glossentry> (the glossary entry topic type)
<glossterm> (the word or phrase)
<glossdef> (the definition of the glossary term)

# NOTE TYPES
<note>
<attention>
<danger>
<caution>
<important>
<tip>
