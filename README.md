Greg Schafer

July 2013

What is it
==========

Spanish verb conjugation game that I originally made for my Spanish class final
project back in 2008. I revisited it in 2013 to add more tenses and make other
small improvements.

Note: The python conjugation scraper scrapes from conjugation.org

Note: The verbs_incl version only includes verbs starting with A through haber
(due to flash file limitations) and has this verblist built-in instead of read
from an external file (for ease of demoing). To use the full or custom
verblists, use cohete_conjugador.swf instead


How to run the scraper
======================

1. Install python

2. Install pip

3. Install virtualenv

4. Make a virtualenv in this repo: virtualenv venv

5. Activate the virtualenv: source venv/bin/activate

6. Install beautifulsoup4: pip install beautifulsoup4

7. Run the program: cd scraper; python scrape_verbs.py in_verbs.txt

Output will be written to the file named "verblist.txt" (sample output is
included)


How to play the game
====================

Play it online at http://grschafer.com/projects/2013/07/14/spanish-verb-conjugation-game/

To run it locally, run the .swf file (you might need a desktop flash player for
this?), which requires a verblist.txt file in the same folder as the swf file.
The verblist.txt file must contain a JSON dictionary of all the
verbs/tenses/forms to use while playing the game.


Other
=====

Cringe at my use of Comic Sans! Bahahaha! =P

...sorry.
