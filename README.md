Hello! And welcome to Johnnys Shared (Via DropBox): dropbox_dev_vault
```
/Users/johnycsh/Dropbox/local_dev_vault
You can think of this somewhat similar to <DOCROOT> in Apache etc
```
(and no, that directory path will not somehow magically update)

I'm having trouble keeping track of what gets stored (or referenced where). I really like obsidian sync, but i also don't understand how it works. So for now I have disabled it to get a better feel for using Obsidian as a shared resource, with the syncronization happening at the filesystem level. In this case, via dropbox. 


All obsidian does is accept the paste buffer, *generate a unique filename/location* for the buffer, write it do disk (./Pasted image 20230118173106.png), and then __auto insert__ a quick reference to it by placing the cursor after a ![[your_file_here]].  In fact, if you reference over that link right there, obsidian will inform you that the referenced file does not exist, and prompt you to create it. Just like a wiki would.

These shallow (simple?) REF-Links illustrate why Obsidian.app *requires* the concept of a **vault**' in the first place. Since Obsidian does __not__ have any out-of-band state tracking mechanism, these relatively simple quick-links must be paired with a 'vault'. 

The 'vault' serves as the equivalent of an Apache DocumentRoot.

Right?



