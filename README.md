![Banner](banner.png)

# macOS-Audio-Ducking-Setup
macOS audio ducking setup blackhole + audio hijack

# To setup
Set the system-wide audio output to the blackhole 2ch driver and then setup audio hijack with an output device and audio ducking.

I keep the order in that setup on purpose. My system sound has to go into the BlackHole driver first, because that is the sound Audio Hijack then works on. Audio Hijack does the ducking and sends the result to my real output device. If I set Audio Hijack up before the system output points at BlackHole, it has no system sound coming in to duck.

```
https://github.com/ExistentialAudio/BlackHole
https://rogueamoeba.com/audiohijack/
```
