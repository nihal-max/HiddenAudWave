# HiddenWave
Embedding secret messages in wave audio file

# What is HiddenWave
Hiddenwave is a python based program for simple audio steganography. You can hide your secret text messages in wave audio file. you can play this audio in any media player and secretly share your private message with any one.

# Requirements
<p>This tool require python3</p>

## Installation

```
git clone https://github.com/Nihal/HiddenWave.git
cd HiddenWave
```
## Usage
<p>Hiddenwave have two python scripts. </p>
<ul>
<li><b>HiddenWave.py :</b> for hide secret information.</li>
<li><b>ExWave.py :</b> for extract secret information for wave audio file.</li>
</ul>

### Hide Secret Information in Audio file

```
python3 HiddenWave.py -f Demo.wav -m "Secret Msg" -o output.wav
```
### Extract Secret Information from Audio file

```
python3 ExWave.py -f output.wav
```

### Video Demo
[![Demo Video](https://i9.ytimg.com/vi/LAVbDnfQD1I/mqdefault.jpg?v=6669c19e&sqp=COyhhbgG&rs=AOn4CLDL3Gr4lEQqrTUKfq0-lVQRTjig4w)](https://youtu.be/LAVbDnfQD1I)
#### For More Video subcribe <a href="http://youtube.com/@BinaryBiteSecurity">BinaryBite Security YouTube Channel</a>
