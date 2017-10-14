Project 3 - Simple Anagram Game, Web-based

Author: Kevin Roeske
Class: CIS322 F17
git: github.com/kevinroeske/proj3-anagrams.git

Server and page respond in real time with each keystroke. Successfully identified words are displayed at the bottom automatically,
no submission gesture is necessary. Displays a success page when the prescribed number of words is identified.


Known bugs:

When the game completes, it logs an error for a bad callback. I haven't been successful in tracking down the logic that causes this,
but it appears to attempt to fetch json on an empty input box, even though no key need be pressed after the last letter
