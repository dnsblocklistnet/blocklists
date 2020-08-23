# What is this?

This is a repository of domain blocklists. It does not contain actual software that will block connections to these domains, merely lists of domains to block.



# How do I use this?

These files are intended to be used either as hosts files, or with DNS lookup blocking software like Pi-hole. If used properly, these files will prevent your computer from finding the IP addresses of the listed websites, making your computer unable to initate a connection. The authors recommend: https://docs.pi-hole.net/

Please note: For even moderately technically proficient users, this sort of block is easy to circumvent. These files only prevent computers from finding out where the websites are located, it doesn't actually stop connections. If a user configures their device to find IP adresses from a different source, they will still be able to connect. See: https://en.wikipedia.org/wiki/DNS_blocking

# Why is this a thing?
The authors are concerned with the impact that conspiracy theroies and other internet plagues are having on the health, well-being, and happiness of people. These blocklists were compiled in an attempt to make such information more difficult to stumble across, and in that way, prevent exposure. 

A lot of misinformation, fake news, conspiracy theroies, and scams are spread via social media. The hope is that use of these blocklists will prevent people from clicking through links on social media that take them to even darker and crazier parts of the internet. These lists are, in one sesnse, an attempt to compensate for the lack of moderation on large socail media websites. We can't prevent other users from posting insane material, but at least we can make it more difficult for their victims to tumble down the rabbit hole.

# Why don't you include a list to block fake news websites?
There are already many extensive blocklists for blocking fake news. You should be able to find them quickly with a simple search. These lists are intended to be more focused, and to fit a specific niche.

# How can I contribute?
Open a new issue here on Github! Please provide a list of domains you think should be included on the blocklists, and why.