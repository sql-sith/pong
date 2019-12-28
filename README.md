pong
====

This is a version of the Kivy pong tutorial, including an APK file for use on Android. It is known to be buggy. For example, let the first serve bounce between the paddles without moving them and the ball speeds up automatically every few bounces. However, before too long one of the sides will score even though you didn't move either paddle and the ball was still traveling horizontally. This happens because the speed of the ball becomes fast enough that the app samples it on one side of the paddle and then on the other side of the paddle, with neither sample showing any collision.

I have no plans right now to fix this. I used this project to teach some high school students a little about Python, and I thought I'd give an Android cross-compiler a try. Definitely not the way to go! :-)
