# Swedish translation for LearnDash

## The problem with the official translation

Just like with most other WordPress plug-ins, adopting LearnDash’s strings for Scandinavian languages isn’t as easy as just replacing some words. LearnDash’s Custom terms for courses, lessons etc. makes it even harder (if not impossible). The Scandinavian languages’ divergent language rules for capitalization aren’t supported at all, and the noun gender rules are hard to adopt.

We tried to fix some of these issues by adding styling tags, e.g. text-transform: lowercase. Unfortunately, styling tags aren’t supported for all strings. Some strings were also totally impossible to translate due to the way vowels change in Swedish compound words. Question is “fråga” and answer is “svar”, but question answer isn’t “frågasvar” but rather “frågesvar”. Hence, the approach with styling tags was a dead end.

## An alternative translation

We realized that the only way to make a Swedish translation would be to hardcode all strings, consequently dropping support for Custom terms. 

Without support for Custom terms, this translation cannot be added to the official language repositories, and it’s therefor hosted as an alternative translation here on GitHub. 

## Installation

Copy the .po and .mo files to /public_html/wp-content/languages/plugins/. 
