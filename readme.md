
[Kivy](https://kivy.org/)
* [KivyMD](https://github.com/HeaTTheatR/KivyMD)
* [Buildozer](https://github.com/kivy/buildozer)


```
pushd /usr/share/python-kivymd/demos/kitchen_sink; python3 main.py; popd
```

![screenshot](screenshot.png)

------------------------------------

Download part of a GitHub repo
* [SO](https://stackoverflow.com/questions/7106012/)
* [DownGit](https://minhaskamal.github.io/DownGit/)

[Git diff w/o +/- sign](https://stackoverflow.com/a/34175594/)
```
git diff --color | sed -r "s/^([^-+ ]*)[-+ ]/\\1/" | less -r
git diff --color-words
```

 (keep commit hash)
```
git bundle create feb58f6.gitbundle HEAD HEAD^
git bundle verify feb58f6.gitbundle
```

[Share git bundle online](https://filebin.net/l3p8omdxyd26pqx9/)

Apply git bundle
```
git log --oneline
git bundle verify /home/darren/.cache/yay/python-kivymd/feb58f6.gitbundle
git pull /home/darren/.cache/yay/python-kivymd/feb58f6.gitbundle
git log --oneline
```

Others
* [com.aefyr.sai](https://play.google.com/store/apps/details?id=com.aefyr.sai&hl=en)

