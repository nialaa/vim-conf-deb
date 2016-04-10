# vim-conf-deb


How to use this config:
==========================


NOTE: maybe it's obvious, but we know details takes hours to find the error.

- Download vim. (sudo apt-get install vim in .deb OS)
- Clone the repo (git clone [url])

Assuming we clone it in your **home directory** (/home/[user]/ or ~/)...

- Go to repo (cd vim-conf-deb)
- Copy .vim folder in ~/ (cp -r .vim ..)
- Copy .vimrc file in ~/ (cp .vimrc ..)
- Open Vim (vim or vim-gnome or whatever you use)
- **If you use Vim Plug previously** --> :PlugClean
- :PlugInstall
- Done!

-----------------------------

You have different color schemes readable for Python and Javascript
development. It's the languages I have already use with it, it doesn't mean that
for other languages, of course.

Candy.vim: http://www.vim.org/scripts/script.php?script_id=282
Distinguished.vim: http://www.vim.org/scripts/script.php?script_id=3529
Monokai.vim: http://www.vim.org/scripts/script.php?script_id=4667
Vividchalk.vim: http://www.vim.org/scripts/script.php?script_id=1891


------------------------------

In .vimrc it's set Monaco font. To install it in Linux systems follow this
steps:

- Go to font directory (cd /usr/share/fonts/truetype/)
- Create Monaco directory (sudo mkdir monaco)
- Go to Monaco directory (cd monaco)
- Download Monaco font (sudo wget http://www.gringod.com/wp-upload/software/Fonts/Monaco_Linux.ttf)
- Build an index file with font added (sudo mkfontdir)
- Exit from Monaco directory (cd ..)
- Create font information caches for fontconfig system (fc-cache)
