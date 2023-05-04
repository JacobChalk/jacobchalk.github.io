---
title: "Epic-Sounds: A Large-scale Dataset of Actions That Sound"
collection: publications
permalink: /publication/EPIC-Sounds
excerpt: 'We introduce EPIC-SOUNDS, a large-scale dataset of audio annotations capturing temporal extents and class labels within the audio stream of the egocentric videos'
date: 2023-02-01
venue: '2023 IEEE International Conference on Acoustics, Speech, and Signal Processing (ICASSP)'
paperurl: 'https://arxiv.org/pdf/2302.00646.pdf'
---

We introduce EPIC-SOUNDS, a large-scale dataset of audio annotations capturing temporal extents and class labels within the audio stream of the egocentric videos. We propose an annotation pipeline where annotators temporally label distinguishable audio segments and describe the action that could have caused this sound. We identify actions that can be discriminated purely from audio, through grouping these free-form descriptions of audio into classes. For actions that involve objects colliding, we collect human annotations of the materials of these objects (e.g. a glass object being placed on a wooden surface), which we verify from visual labels, discarding ambiguities. Overall, EPIC-SOUNDS includes 78.4k categorised segments of audible events and actions, distributed across 44 classes as well as 39.2k non-categorised segments. We train and evaluate two state-of-the-art audio recognition models on our dataset, highlighting the importance of audio-only labels and the limitations of current models to recognise actions that sound.

[Project Webpage](https://epic-kitchens.github.io/epic-sounds/)
[Paper](https://arxiv.org/pdf/2302.00646.pdf)
[Source Code](https://github.com/epic-kitchens/epic-sounds-annotations)