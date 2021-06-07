# NeuroSINDy

## Overview
A library to do SINDy in an integrated environment across multimodal neural recordings, DBS control, and measurement errors.

## Requirements


## Installation


## Uses

### EEG inference
Dynamics in the brain contribute towards the generation of scalp EEG, and one of the things EEG researchers care the most about is how the EEG measurements reflect what's happening at the measurement's *source*.
Dynamics can help us better infer the source by providing additional structure as we try to figure out what's going on.

SINDy can play an important role in helping us find the underlying source dynamics from EEG recordings.

### Tracking Dynamics (simulated)
One use case of this is to identify dynamics directly from raw neural recordings.
This is best illustrated in a simulated experiment

### Empirical Dynamics
Use of NeuroSINDy in empirical cases are more difficult, largely due to both the noise as well as the 'dimensional decompression'.
This use case relies on a different paper: Champion et al. 2019.
In this paper an extra layer is added.
The runtime expands from ~20 seconds in the above case to approximately 4 hours.

