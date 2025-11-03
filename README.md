# Mood-based-music

# Introduction
Mood Based Music is an interactive code project built in TunePad (Python) that allows users—especially those who may struggle with rhythm or musical timing—to easily create their own music.

Inspired by a melody from Jennie – Like Jennie, this project demonstrates how code can be used to turn a single melody into a rhythmically structured musical base. By layering instruments such as guitar, piano, and drums, the system produces a simple, steady, and engaging beat.

Once the base rhythm is generated, any user can experiment with notes and patterns on top of it to compose their own joyful or expressive new melodies. The goal of Mood Based Music is to make music creation accessible to everyone, regardless of their musical background or sense of rhythm.

# APIs & Core Functions

playNote(note, beats, instrument, velocity) — play specific notes or chords

setTempo(bpm) — set tempo for the entire project

moveTo(position) — jump to a specific time position in the playback timeline

getPlayhead — get the current playback position

rest(duration) — pause between notes

loop() and for — control rhythmic repetitions

runInParallel() — execute melody and rhythm simultaneously
