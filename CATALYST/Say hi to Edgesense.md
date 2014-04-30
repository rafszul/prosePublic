Say hi to Edgesense
Alberto's picture
Submitted by Alberto 3 days ago

As a part of my quest towards designing for emergent social dynamics in online conversations, I got involved in a EU project on collective intelligence called CATALYST (wearing my Wikitalia hat). I head a small team of two working on – you guessed it – network analysis for the masses. Specifically, we are making a Drupal module for social network analysis of online conversations, based on Python, Networkx, sigma.js and D3. @Luca Mearelli is doing the heavy lifting. We call it Edgesense – the name was chosen by Luca, and has nothing to do with Edgeryders, though it does fit rather neatly.

@Matthias, Luca has produced a working demo that eats JSON files extracted by me using Views Datasource, and we are now looking into integrating it into Drupal. Since we have been using Edgeryders (2012) data to test the demo, he has requested the authorization to set up an exact copy of Edgeryders on his own server to work on the integration. For this he needs:

the Edgeryders platform code
a dump of the Edgeryders database
Can he be accommodated? I take responsibility for data protection. As far as the code is concerned, I believe you maintain a GitHub repository from which the code can be downloaded, so that should be no problem. @La_Gaia, you should like this too: barring accidents, in a month we will have basic network analysis support, updated daily. More or less in the same amount of time we should be able to release an alpha as a Drupal module, so that anybody can use it. 

 https://edgeryders.eu/sites/default/files/Edgesense_1st_screenshot.jpg

Image: 

Like
like0
Topics: 
Edgesensenetwork analysis
Groups: 
Edgeryders Dev & Testing
Log in or register to post comments
Comments

Hi @Mathias Alberto has
Submitted by Luca Mearelli on 3 days ago
Luca Mearelli's picture
Hi @Mathias Alberto has explained already what we are working on. It would be really precious for the development to be able to work on a copy of the edgeryders site (it'd give us an environment as close as possible to what we'd find in a live, production site), so let me know if you need more informations or anything.

Thanks!

like0
Log in or register to post comments
Hi Edgesense, nice to meet ya :)
Submitted by Matthias on 3 days ago
Matthias's picture
Nice clean and informative interface ... I think I understand how to use it. Bottom right graph is probably "community's share of content"?

I can provide a database dump, with limitations to protect privacy of our community members: I will clean out all e-mail addresses and real names, and replace usernames with pseudonyms. I will also leave only the public groups. The idea is to create a database dump that only contains the Creative Commons licenced stuff, so that we are able to offer it for public download as well. For others to analyze, but also because the database contains most of the Drupal configuration, without which the code repository is pretty useless.

I can provide this stuff on Tuesday. Tell me if I should prioritize it higher.

(For the Drupal integration, if and when the Edgesense interface will be available to non-admins, note that the non-public content needs to be excluded from these views as well.)

like0
Log in or register to post comments
More than adequate
Submitted by Alberto on 3 days ago
Alberto's picture
You rock, Matt – but we knew this before. 

Tuesday is more than adequate. Luca and I will be in Germany for a consortium meeting from Monday to Wednesday, so Thursday is the earliest we can look at it. Incidentally, are you anywhere near Wuppertal? It would be nice to meet for a beer.

like0
Log in or register to post comments
 the anonymized dump would
Submitted by Luca Mearelli on 3 days ago
Luca Mearelli's picture
yes the anonymized dump would work perfectly! Thanks Matthias smiley

like0
Log in or register to post comments
AMAZING.
Submitted by La_Gaia on 3 days ago
La_Gaia's picture
you guys rock!

like0
Log in or register to post comments
!!!
Submitted by Ben on 2 days ago
Ben's picture
I'm excited!

like0
Log in or register to post comments
"Living tech", remember?
Submitted by Alberto on 2 days ago
Alberto's picture
Edgesense is part of a strategy to tool up the Edgeryders community website to do the sort of distributed knowledge work stuff that we like. It may fail, but we are pursuing it with a pure heart, and pouring into it substantial amounts of work. You, @Ben, can now see why I dislike any maneuvre that pulls interaction away from Edgeryders. Here, content is preserved and re-used to create metacontent (like validation via inference on network structure); elsewhere, it typically is not. I would be glad to tank the damn thing myself and move over to a platform because of better tools for detecting and interpreting emergent social dynamics; but invariably, when people pull away it is because of user experience considerations.  

Hah! I still (ok, barely) remember pre-Internet electronic communication, BBSs, dialup connections, installation floppy disks etc. People wanted to reach out, so they put up with all of the gritty tech. How is it that the possibility to add functionalities like Edgesense are never factored in these conversations? When did we get so spoilt for bloody Ajax?

like0
Log in or register to post comments

<https://edgeryders.eu/edgeryders-dev/say-hi-to-edgesense#comments>