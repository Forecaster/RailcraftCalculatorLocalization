RailcraftCalculatorLocalization
===============================

Railcraft Boiler calculator localization project

This is for the new boiler calculator localization system to allow people to contribute with translations, similar to the railcraft localization project.

There is a default english.lang file demonstrating the formatting. Copy this and use as a template for your translation.

The file name has to be lower-case.

Comment lines that begin with // are ignored by the parser along with empty lines. Feel free to add as these as you please.

The syntax for a string is id=string.

The "string" part is what you would translate.

To prevent html-injection no html tags are allowed in the strings. These are stripped out during parsing.

Excluded are the <o> and <c> tags which is are custom tags used to apply text styles to specific strings.

In some strings you will find words (mostly names) preceeded by a $ sign. These are used to insert links into the strings. They must not be altered.

For example in the string for "footer.formula", the $wiki will be replaced with "\<a href='http://railcraft.wikispaces.com/Steam+Boiler+%28Device%29'>Railcraft Wiki\</a>" during parsing.

If you have any questions you may find me in #railcraft on the esper.net IRC-network.
