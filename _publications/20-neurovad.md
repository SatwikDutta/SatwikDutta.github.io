---
title: "NeuroVAD: Real-Time Voice Activity Detection from Non-Invasive Neuromagnetic Signals"
collection: publications
permalink: /publication/20-neurovad
excerpt: ''
date: 2020-04-16
venue: 'Sensors 2020, 20, 2248'
paperurl: 'https://doi.org/10.3390/s20082248'
author:  'Dash, D.; Ferrari, P.; <b>Dutta, S.</b>; Wang, J.'
---
Neural speech decoding-driven brain-computer interface (BCI) or speech-BCI is a novel paradigm for exploring communication restoration for locked-in (fully paralyzed but aware) patients. Speech-BCIs aim to map a direct transformation from neural signals to text or speech, which has the potential for a higher communication rate than the current BCIs. Although recent progress has demonstrated the potential of speech-BCIs from either invasive or non-invasive neural signals, the majority of the systems developed so far still assume knowing the onset and offset of the speech utterances within the continuous neural recordings. This lack of real-time voice/speech activity detection (VAD) is a current obstacle for future applications of neural speech decoding wherein BCI users can have a continuous conversation with other speakers. To address this issue, in this study, we attempted to automatically detect the voice/speech activity directly from the neural signals recorded using magnetoencephalography (MEG). First, we classified the whole segments of pre-speech, speech, and post-speech in the neural signals using a support vector machine (SVM). Second, for continuous prediction, we used a long short-term memory-recurrent neural network (LSTM-RNN) to efficiently decode the voice activity at each time point via its sequential pattern-learning mechanism. Experimental results demonstrated the possibility of real-time VAD directly from the non-invasive neural signals with about 88% accuracy.
