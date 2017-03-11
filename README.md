# cardprinter
A small headless webapp for displaying printable pages for a customizable card game. Uses jQuery and handlebars.js

To prepare a 3x3 card sheet for printing, pass an integer as a query to the file (e.g. index.html?0 to start at the beginning, or index.html?4 to start at the 5th card) to display the card at that index plus the next 8 cards in the list. Also, configure your printer to not add margins.

Pass no query (as normal) to see the whole list.

Currently hosted at http://davidhusa.com/mao