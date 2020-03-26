# Combined English and Dutch dictionary

Based on

* https://github.com/marcoagpinto/aoo-mozilla-en-dict
    * containing 87571 words

and

* https://addons.mozilla.org/en-US/firefox/addon/woordenboek-nederlands/
    * containing 173577 words

for a total of

87571 + 173577 = 261148 words

# How to

1. Simply copy all words from one `.dic` file into the other
    * The first line represents the number of words, so don't copy that. Add those two first lines together and that's your new word count.
2. Combine the `.aff` files
    * Keep one `SET UTF-8`
    * Choose the `TRY` for your most-used language
    * Combine `ICONV` statements (I just kept the Dutch ones because all the english ones were in there)
    * Then simply copy all the rest to the end

More info here: https://superuser.com/questions/108177/how-do-i-make-firefox-spellcheck-in-multiple-languages-simultaneously
