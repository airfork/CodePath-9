# Project 9: HoneyPot

> Objective: Setup a honeypot and intercept some attempted attacks in the wild

## Honeypot(s) Deployed
I deployed the one that we deployed in the assignment, MHN, as well as a honeypot that I found called [HoneyPy](https://github.com/foospidy/HoneyPy). 

## Issues Encountered
The only issues that I encountered were centered around the initial installation MHN admin application. This took me a lot of time to figure out, as the GitHub page provided included a script that referenced a GitHub page that had been deleted. I followed the instructions on the main MHN page, but was unable to get anything to work. It was only until I was given a proper link to the admin console several days that it worked.

## Summary of Attacks
I received a lot of attacks on both of my honeypots from all over the world. A lot of attacks seemed to be centered from France, Canada, the UK, and Russia. The actual details of the attacks are very much unknown to be, but all of the ones I saw were using the pcap protocol.

## Questions about data collected
The only unresolved question about the data that I created is the meaning of the identifier field in each JSON object. I am think it just that every attack gets an ID to separate it from other attacks, but I was unsure as it could also be the identifier for a specific type of attack. 


