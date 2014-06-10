# Fall - a game

From the original documentation:

> Help Don the Daredevil Dot steer clear of the sides of the bottomless Crevasse of Stars, into which he has flung himself in search for fame and glory. Sadly, he is very nearsighted, so since you can't see the shape of the pit underneath him very well, you'll just have to try and keep him clear of the walls. Don will happily collide with the walls five times before calling it quits and retiring to a less demanding pastime elsewhere in your computer.

I (Jason McIntosh, jmac@jmac.org) wrote _Fall_ as an entry to a contest run in the summer of 2000 by _The Perl Journal_, a print magazine sadly now defunct. It meets the challenge of implementing a game in 512 bytes or fewer. _Fall_ clocks in at 494 bytes, if you don't count the trailing newline. (Doubtless it could be smaller still; I likely didn't know about the `?:` operator when I wrote this.)

I have worked with Perl nearly every day since the late 1990s. I pride myself on crafting clear, maintainable code. This project represents the only time I have written stereotype-affirmingly horrendous Perl on purpose.

_Fall_ did not win the contest. However, it probably helped land me the job that saw me move from central Maine to Boston, where I have lived ever since. 

## Prerequisites

Perl, perhaps 5.6 or greater. (It still works on 5.18.1, by gar.)

## Usage

Just type `perl fall.pl` at the command line.

## Gameplay

The following text comes from the game's original, 2000 release.

### Controls

Hit ENTER to toggle the direction of Don's fall: left or right. You can't make him fall straight down, but you can kinda fake it by holding down the ENTER key. However, this straight plunge makes Don especially aerodynamic, and may greatly increase his downward velocity. Be careful!

### Scoring

You score one point for every Don-length that Don falls before he bumps five times into the starry walls, at which point the game shall display your final score.

### Tips

Don always begins his plummet from the left lip of the crevasse, and starts to fall rightwards.

If Don still has lives left after smacking into a wall, he'll bounce off of it and start falling in the opposite direction.

It is said that the Star Crevasse rather resents folks jumping into it, and might sometimes try to confuse and endanger adventurous divers by displaying nonsensical illusions. Stay alert!

## Copyright and credit

The work in this repository is copyright &copy; 2000-2014 by Jason McIntosh. Permission is hereby granted to copy and modify the code (but not this documentation) for your personal use.
