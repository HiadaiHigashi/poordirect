# poordirect
almost osu!direct for linux

result: https://youtu.be/BpNz6G3xhbA
## Dependencies
* curl

## Setup
```
cp poordirect.desktop ~/.local/share/applications/
sudo cp poordirect /usr/bin/
xdg-settings set default-web-browser poordirect.desktop
```
make sure that the right browser is here (eg firefox/chrome)
```
sudo update-alternatives --config x-www-browser
```

install https://addons.mozilla.org/en-US/firefox/addon/cookies-txt/ extension, make sure you are on a new site then click on the extension icon and save the file as ".cookies.txt" in home folder, edit the file so that there is nothing superfluous (make it look like the one here).

test with
```
poordirect https://osu.ppy.sh/b/1494771
```

Done! not working? write me Hiadai_Higashi#6284
