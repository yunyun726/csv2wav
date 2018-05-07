# csv2wav - A minimalistic csv to wav convertor.
This tool aims at converting csv data to simple wav files.

## Example use
1. Clone or download and extract this repo.
1. Open the supplied file `square.ods` in Libre Office.
1. Hit `File` -> `Save as...`
1. Select file format `Text CSV (.csv)`.
1. Save the csv version into the same directory.
1. Now open up a command prompt in that folder.
1. And run: `csv2wav.exe sine.csv 0 sine2.wav 44100` (the parameters being input file, csv data column, desired output file and input sample rate)
1. A file named `sine2.wav` should have been produced.
1. When open it in an audio player, you should here a one second long, beep-like sound of 440Hz.
