# HiddenWave
Embedding secret messages in wave audio file

# What is HiddenWave
Hiddenwave is a python based program for simple audio steganography. You can hide your secret text messages in wave audio file. you can play this audio in any media player and secretly share your private message with any one.

# Requirements
<p>This tool require python3</p>

## Installation

```
git clone https://github.com/nihal-max/HiddenAudWave.git
cd HiddenWave
```
## Usage
<p>Hiddenwave have two python scripts. </p>
<ul>
<li><b>HiddenAudWave.py :</b> for hide secret information.</li>
<li><b>ExtractorAudWave.py :</b> for extract secret information for wave audio file.</li>
</ul>

### Hide Secret Information in Audio file

```
python3 HiddenAudWave.py -f Demo.wav -m "Secret Msg" -o output.wav
```
### Extract Secret Information from Audio file

```
python3 ExtractorAudWave.py -f output.wav
```

### Video Demo
[![How to control android camera](https://img.youtube.com/vi/LAVbDnfQD1I/0.jpg)](https://www.youtube.com/watch?v=LAVbDnfQD1I)
#### For More Video subcribe <a href="http://youtube.com/@BinaryBiteSeccurity">Binary Bite Security YouTube Channel</a>
