# soundSet_itk

A [Soundset](http://doc.aldebaran.com/2-4/naoqi/audio/alaudioplayer.html#soundset) for Pepper.

## Installation

Open `choregraphe/soundset_itk.pml` in Choregraphe and upload to robot.

## Usage

Load Soundset (cf. http://doc.aldebaran.com/2-4/naoqi/audio/alaudioplayer-api.html):

```python
audioPlayer = self.session("ALAudioPlayer")
audioPlayer.loadSoundSet("itk")
```

In dialog (cf. http://doc.aldebaran.com/2-4/naoqi/interaction/dialog/dialog-syntax_full.html#runsound):

```
u:(e:onStart) ^runSound(itk/drumroll)
```
