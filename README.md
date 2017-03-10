# EmUGen
A lexicon builder in Excel VBA based around manipulating emic units.

## Introduction
Many conlangers build out their lexicon in spreadsheets, commonly in MS Excel. External tools are generally used to help generate the lexicon, and then these words are recorded in their Excel spreadsheet. I wanted to internalize these tools to provide a more integrated environment for lexicon development, so I created EmUGen - the Emic Unit Generator.

##What are Emic Units?
An [emic unit](https://en.wikipedia.org/wiki/Emic_unit) is "an invariant form obtained from the reduction of a class of variant forms to a limited number of abstract units" (Nöth, 1995). In international standard, emic units are basic building blocks of language, like a *phoneme*, a *grapheme*, or a *morpheme* among others. These "-emes" form the basic parts of language, whether written or spoken, and when generating your own conlang, they are the parts you work with in order to form a cohesive language.

##Basic Use
EmUGen works inside Excel using VBA. You define the emic units you want to work with to form your words. These can be phonemes like vowels and consonants, graphemes such as characters, morphemes such as suffixes. EmUGen is scalable, allowing you to generate smaller parts, and then generate larger parts with those smaller parts, *ad infinitum*. For example, you can use EmUGen to randomly generate syllables, then words, and then generate sentences using those words.

