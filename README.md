# everrite
Automatic IP blocker, based on IPs that have attacked my honeypot.

If your IP is blocked by this mistakenly (due to pesky ISPs with their dynamic IPs) open an issue and it will be removed promptly.

Setup is fairly simple, clone the repo and run the blocker, for extra measure, add
*/30 * * * * rm -rf /home/YOURUSERNAMEHERE/everrite && git clone https://github.com/CheekiBreeki95/everrite.git /home/YOURUSERNAMEHERE/everrite\
*/35 * * * * bash /home/YOURUSERNAMEHERE/everrite/master-block.sh\
making sure to change YOURUSERNAME here to your username! Of course you can change the path to anything but the home path is the easiest for the case of permissions. Also be aware this method is unsafe in the case I get hacked or go crazy and mess with the script, so its up to you whether or not you want to go this route!
