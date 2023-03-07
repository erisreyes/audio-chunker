# audio-chunker
chunk video into segments into 30 seconds using python

Audio Chunker
The Audio Chunker is a Python script that can be used to split audio files into segments of a fixed duration. This is useful when working with large audio files that need to be processed in smaller chunks.

Usage
To use the Audio Chunker, simply run the chunk_audio.py script and specify the input and output paths, as well as the desired segment duration in seconds. For example:  python chunk_audio.py --input /path/to/input/file.wav --output /path/to/output/directory --duration 30

This will split the input audio file into segments of 30 seconds each, and save each segment as a separate file in the output directory.

Requirements
The Audio Chunker requires the following Python packages to be installed:

pydub
click
You can install these packages using pip:  pip install pydub click

License
The Audio Chunker is released under the MIT License. See the LICENSE file for more information.
