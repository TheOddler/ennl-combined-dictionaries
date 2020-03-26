# Combined English and Dutch dictionary

Based on

* https://github.com/marcoagpinto/aoo-mozilla-en-dict
    * containing 87571 words

and

* https://addons.mozilla.org/en-US/firefox/addon/woordenboek-nederlands/
    * containing 173577 words

for a total of

87571 + 173577 = 261148 words

# How to install

Note: xpi file already created in this repo, so you can go straight to `3.` if you want.

1. Create a zip file from all the files.
2. Rename the zip file `.xpi`
3. Place this file into `%AppData%\Mozilla\Firefox\Profiles\{profile}\extensions`
4. Restart FireFox

# How to make your own

1. Simply copy all words from one `.dic` file into the other
    * The first line represents the number of words, so don't copy that. Add those two first lines together and that's your new word count.
2. Combine the `.aff` files
    * Simply copy one `.aff` file's content to the end of the other

More info here: https://superuser.com/questions/108177/how-do-i-make-firefox-spellcheck-in-multiple-languages-simultaneously
