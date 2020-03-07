# How to self-publish your talk or poster presentation as a video

This is a collection of pointers about creating and publishing videos of talks and poster presentations that may come in handy at a time of conference cancellations on short notice.

## Things to keep in mind

_**Don't over-do it:**_ Your video is a stand-in for an on-stage talk or a short poster pitch. Just as these are hardly ever presented in a perfect performance, your video does not need to be perfect either.

_**Have a pointer:**_ If you would normally present your materials with a pointer, then do so in the video as well.

_**Have a sound check:**_ Record a short video to test microphone sensitivity (make sure to speak loud and low, have a few clicking sounds) and ensure that there's not too much background noise in the video.

## Recording and (basic) editing of your video

### Ubuntu Linux

With _Ubuntu Linux newer than 18.04_, you can start recording your screen [by pressing `Ctrl+Alt+Shift+R`](https://help.gnome.org/users/gnome-help/stable/screen-shot-record.html.en). The default duration for Gnome screen casts is only 30 seconds but can be changed [from the graphical user interface](https://askubuntu.com/a/919808) or [on the command line](https://askubuntu.com/a/1131696):
```shell
$ gsettings set org.gnome.settings-daemon.plugins.media-keys max-screencast-length 1800
```

### Mac OSX
On Mac OSX, you can use the [builtin screen shot tool accessible via Shift-Command (⌘)-5](https://support.apple.com/en-us/HT208721) to record videos. (Make sure to turn on the microphone via a click on `Options ` before recording.) After you stop the recording, you'll be able to re-play and trim the video.

### Windows 10

On Windows 10, there is [built-in video capture via the Xbox game bar](https://support.microsoft.com/en-us/help/4027180/windows-10-record-a-game-clip-with-xbox-game-bar). To edit the video after recording, [you can use the Photos app](https://support.microsoft.com/en-us/help/27916/windows-10-edit-photos-videos).

## What to publish?

From a viewer's perspective, it would be ideal if you published 

- the video with your presentation, along with
- your materials (slides or poster) in the original format (ODP / PPT / PPTX, SVG / INDD, …) and as a PDF (to minimise software requirements for the viewer),
- as well as your speaker notes.

You might have a different preference regarding the publication of your original materials.

## Where to publish?

_**[Zenodo.org](https://zenodo.org)**_ ([Wikipedia article](https://en.wikipedia.org/wiki/Zenodo)) is funded under the European [OpenAIRE program](https://en.wikipedia.org/wiki/Framework_Programmes_for_Research_and_Technological_Development#OpenAIRE) and lets you publish collections of different media and data files under a common DOI with _minimal effort_. Sadly, the website does not provide built-in video preview.

_**[Figshare.com](https://figshare.com)**_ ([Wikipedia article](https://en.wikipedia.org/wiki/Figshare)) is a privately owned publishing platform that also allows for publishing collections media and data files under a common DOI. In contrast to Zenodo, it has built-in preview for most of the relevant formats.

_**[YouTube.com](https://youtube.com)**_ can be used for an accompanying publication of your video that enhances accessibility via the built-in autogeneration of closed-captions.
