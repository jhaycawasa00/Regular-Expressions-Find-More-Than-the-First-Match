# Description

Regular Expressions: Find More Than the First Match
So far, you have only been able to extract or search a pattern once.

let testStr = "Repeat, Repeat, Repeat";
let ourRegex = /Repeat/;
testStr.match(ourRegex);
// Returns ["Repeat"]
To search or extract a pattern more than once, you can use the gflag.

let repeatRegex = /Repeat/g;
testStr.match(repeatRegex);
// Returns ["Repeat", "Repeat", "Repeat"]


# Instruction

Using the regex starRegex, find and extract both "Twinkle"words from the string twinkleStar.

Note
You can have multiple flags on your regex like /search/gi


# Test

Your regex starRegexshould use the global flag g
Your regex starRegexshould use the case insensitive flag i
Your match should match both occurrences of the word "Twinkle"
Your match resultshould have two elements in it.


# Challenge Seed
let twinkleStar = "Twinkle, twinkle, little star";
let starRegex = /change/; // Change this line
let result = twinkleStar; // Change this line


# Solution
let twinkleStar = "Twinkle, twinkle, little star";

let starRegex = /twinkle/gi; // Change this line

let result = twinkleStar.match(starRegex); // Change this line
