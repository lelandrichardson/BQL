BQL: A SQL Superset Language
======

### Resources ###

[Motivations Blog Post - Tech.pro](http://tech.pro/blog/1917/a-sql-superset-language-proposal)


### Key Benefits ###

-- todo

### Language Goals ###

-- todo

### Syntax ###

# Getting started

To try out the bql parsing:

* Open the sln in visual studio 2013
* Mark "030.Irony.GrammarExplorer.2012" as the startup project (right-click, set as startup)
* Hit run (f5)
* This will fire up the grammar explorer (more info at the original site: http://www.codeproject.com/Articles/22650/Irony-NET-Compiler-Construction-Kit )
* Add the BQL grammar dll
	* Click the "..." button next to "grammar"
	* click "Add grammar" in the dropdown that appears
	* browse to the dll you just compiled at `BQL.Irony.Grammar\bin\Debug\BQL.Irony.Parser.dll`, click ok
	* ok the "select grammars" popup (it's already selected, you should see BQL ticked in the list)
* Flip to the "test" tab
* click "Load..."
* select `example.bql` from the root of this solution
* click "Parse"
* poke around in the "parse tree" window.
