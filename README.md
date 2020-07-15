# mp3_recorder

# Inspiration
There are several solutions to the recording mp3 in javascript.This project is derived from
[mp3lameencoder](https://github.com/higuma/mp3-lame-encoder-js) which is itself inspired from 
[wavrecorder](https://github.com/mattdiamond/Recorderjs) .However,sometimes the beginners don't 
want to understand the process behind it and just implement it.This is for the those lazy developers like me.

# Some things to consider though even if you are lazy

* [webaudiopolicy](https://developers.google.com/web/updates/2017/09/autoplay-policy-changes#webaudio)

* You would have to press the audio context button first.If you dont, it wont work,so go figure out for your use case.

* Once,you get the satisafaction of recording it in mp3,please go ahead and research how it was done.
