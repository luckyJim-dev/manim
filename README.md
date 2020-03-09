### install (Mac OSX)
1. install [MacTeX](http://www.tug.org/mactex/mactex-download.html)
2. install [HomeBrew](https://brew.sh/)
3. using HomeBrew install ``FFmpeg``,``Sox``,``cairo``,``py3cairo``(for Python3),``pkg-config``.
```sh
# install ffmpeg
brew install ffmpeg

# install sox
brew install sox

#install cairo
brew install cairo

#install py3cairo(Python 3.x) or py2cairo(python 2.x)
brew install py3cairo

#install pkg-config
brew install pkg-config
``` 
4. git clone this sourcecode and run
```sh
git clone https://github.com/3b1b/manim.git
cd manim
pip3 install -r requirements.txt
python3 manim.py example_scenes.py SquareToCircle -pl
```