# Real-time Speech Analysis
Python's [parselmouth](https://parselmouth.readthedocs.io/en/stable/) package makes it easy to use Praat for speech analysis, which is useful for measuring pitch and formants. However, these measurements are difficult and can be glitchy or irregular when coming from real speech audio. It's especially tedious to identify problems, because this requires making a new recording, running the measurements, and then examining the issues after the fact. There's no immediate feedback, making it hard to identify and fix problems on the spot.

The goal of this tool is to make it easier to find and address issues as they happen. You can run it, start speaking, and immediately see the pitch and formant measurements. The purpose of this tool, then, is not to create a perfectly clean pitch and formant measuring tool (though that could be a future extension); instead, it helps to see where the measurements go wrong as they happen.

In the file 'realtime_speech_analysis.ipynb', each cell introduces a new real-time audio analysis tool. Using the '%matplotlib notebook' command, it runs in Jupyter Notebook.
