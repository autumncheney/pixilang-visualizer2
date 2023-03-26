# NOTICE: this github repository has been archived. the newest updates can be downloaded from [my gitea repo](https://git.acheney.xyz/acheney/pixilang-visualizer2)

# abstract
this is the second version of my pixilang visualizer, with a revamped look and config options! i kept the old one up because this one probably isn't as computationally efficient as the first one (it does look good if you bake it to a video though!)

it uses a few media files, including two logos and a cover (all `.png` files) and the `.wav` file to be visualized. additonally, it also takes text for the song attribution, which is specified in the config. it takes these and produces a video the length of the audio file, with a spectrum, flashing background, cover and logo art, song info, and transition effects at the beginning and end of the song

just replace the files (and change the config section if necessary) and be on your merry way! if you're on a *nix os with ffmpeg, you can uncomment the `demo_video_export` to produce a video file to upload wherever

see it in action [here](https://www.youtube.com/watch?v=KaGbA-CDJ1s)

# how to use

1. clone this repository and unarchive it
2. replace the media files, the ones in this repo are placeholders. the `artist.png` is the logo shown first, the `logo.png` is shown second. in one use case, if you're a label, the `logo.png` is your logo and the `artist.png` is your artist's logo. the `song.wav` is the audio to be visualized, and the `cover.png` is the cover art for the audio
3. if necessary, edit the `boot.pixi` and change the config variables (everything between `-- CONFIG BEGIN --` and `-- END CONFIG --`) to your liking. everything has comments explaining what they do. i'll probably add more variables to customize in the future
4. grab pixilang from [here](https://warmplace.ru/soft/pixilang/) and run the binary for your operating system. it's free (at least for desktop operating systems)
5. in pixilang, navigate to where you extracted the repo and run the `boot.pixi` file
6. enjoy!

# credits
the main visualizer was written by me, with help from nightradio, silent broadcast, and others. the other pixilang libraries were written by nightradio and are under the mit license. the placeholder assets were made by me
