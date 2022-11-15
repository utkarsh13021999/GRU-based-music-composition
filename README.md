# GRU-based-music-composition
ABC notation is a shorthand form of musical notation. In basic form it uses the letters A through G, letter notation, to represent the given notes, with other elements used to place added value on these – sharp, flat, the length of the note, key, ornamentation. To learn more about char ABC Notation in https://en.wikipedia.org/wiki/ABC_notation

The mechanics of the text generation uses a Char-RNN based generator, which learn about the pattern about characters appear of the char ABC notation in Music. When it is trained then, it will able to generate the music char abc notation which seems to new compose music that the network learn.

# Dataset used 
Irish Folk Music
As a lover of folk tunes, particularly Irish tunes, I found these datasets immensely helpful.

  1.  O'Neill's Irish Music dataset (Source: http://trillian.mit.edu/~jc/music/book/oneills/1850/X/ )
  2.  Cobb's Irish Music dataset (Source: http://cobb.ece.wisc.edu/irish/Tunebook.html )
  3.  Nottingham Music dataset (ABC version of Nottingham music dataset: http://abc.sourceforge.net/NMD/)

For this project, I have used Nottingham Music Dataset.

# Results
![training loss over epochs](https://user-images.githubusercontent.com/100249684/155656907-6f6dd897-debd-4eb2-b3e9-505ba30145b8.PNG)

![accuracy over epochs](https://user-images.githubusercontent.com/100249684/155656949-a6c1c082-1f38-4d31-afa7-c54f606e2c07.PNG)

![output](https://user-images.githubusercontent.com/100249684/155657024-90d76cdc-3631-4401-b963-581fa6a022b6.PNG)
$ python sample.py


Output musical notes and audio from https://www.abcjs.net/abcjs-editor.html

# Primary Aim

Primary Aim of this project was to learn and understand basics of RNNs,LSTMs and GRUs through an interesting project.

# Applications of this Project 
1. Can be used in a solo jamming session by a musician for a replacement of a pianist.
2. Can be used as copyright free music by content creators like Youtubers
3. Can be used for Alarms and ringtones.

# Future Work
1. Transformer and Bert based model can be implemented for this project.
2. Learn from Google Magenta Project
