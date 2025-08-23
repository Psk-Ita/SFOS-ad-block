# SFOS-ad-block
ad block script for Sailfish OS


### what is this?
a script to update hosts files  automagically (kind of ad-away via shell)

### why?
I have my custom mods, this is "sandard" enought to be a public module

### how it works?
the defautl config is based od [StevenBlack's hosts](https://github.com/StevenBlack/hosts), it contains:
<ul>
<li>alternates/porn</li>
<li>alternates/social</li>
<li>alternates/fakenews</li>
<li>alternates/gambling</li>
</ul>

you can customize the list editing **ad-block.txt** file

**do-check.sh** is designed to run max once a day (it can be scheduled)
**ad-block.sh** generate and apply hosts file

that's all.

#
Enjoy!

