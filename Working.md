# Introduction #

Attempts to describe the technical approach employed to make this thing actually work.


# Goal #

Yes this is hard, yes this will be difficult to get working (if possible at all) but I've been here before and had some promising results.

There are numerous examples of taking WAV based music and converting to MIDI - that's in the same ballpark as this work. However, the difference with this project is:

  1. The focus is on speech
  1. Success is recognisable speech

I am not necessarily trying to replicate quality or tone - I just want to make sure it is understandable.

# Technical Approach #

  1. Record audio as waveform, e.g. PCM
  1. Convert to frequency map, think of spectrum analyser over time
  1. Convert frequency map into vector representation
  1. Render vector representation, e.g. using MIDI