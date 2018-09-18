Lightweight Pure DMMs with video input.

The software is in Processing 2.2.1 and uses `video` library. 

(You might want to mute the sound, especially if you experience "stuttering sound" from your movie video loop (I have this problem on my Windows 10 laptop).)

1) See https://github.com/anhinga/fluid/blob/master/atparty-2018/surreal_webcam/README.md
for documentation on the way movies are hooked into Processing.

2) This software is based on
https://github.com/anhinga/fluid/tree/master/atparty-2018/game_of_afterlife/afterlife_conway_2_seed

(See https://github.com/anhinga/fluid/tree/master/atparty-2018/game_of_afterlife for history.)

`afterlife_conway_2_video` should work as is (the movie is fed into the second output of the DMM, and interesting patterns are observed on top of bistability effects on the original `afterlife_conway_2_seed`).

`afterlife_conway_2_video_self` requires one to copy the `data` directory with the movie it contains from `afterlife_conway_2_video` to work (the movie is fed straight into the first output of the DMM; the patterns are somewhat less interesting in this mode, but worth studying).
