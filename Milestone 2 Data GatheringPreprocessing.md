# Digital Musicology - Milestone 2: Data Gathering/Preprocessing

## Code
We were able to find Josh McDermott’s code that was used in the original
experiment[J. McDermott, E. Simoncelli, 2011]. This algorithm proceeds in the
following way:

## Statistics extraction

1. Cochlear decomposition of the orginal sound, by applying 30 bandpass filters
    on a logarithmic frequency scale.
2. Amplitude envelope extraction
3. Cochlear compression
4. Channel-specific decompostion of the envelope modulation, by applying 20
    bandpass filters per, starting an order of magnitude lower in the modulation
    frequency than the classic frequency filtering
5. Extraction of spectral power per band & band correlation

## Synthesis

1. Choice of a starting sound, which can be white noise, pink noise, water noise,
    etc
2. Iterative Synthesis process, in which the starting sound (noise) is modified
    iteratevely until it matches the constraints, i.e. the statistics computed before.

For more details on the algorithm, see [J. McDermott, E. Simoncelli, 2011].
The coding environment/language is Matlab

This algorithm performs very well with sound textures, i.e. sounds that don’t
change over time. That means its statistics remain the same over the whole
duration of the sound. In a future step, we will modify the algorithm in the
following way:
Instead of computing the statistics/sythesis for a whole texture, an extraction/
synthesis per time window (which size can be modified) is planned. This will
permit us to modify the input, and use sounds that change over time, for instance
musical pieces.
In this way, we will be able to extend our project to musicology. We will be able to
test which statistics our characteristics of the sound preserve (or not) certain
musical aspects of the original piece. Since we are not there yet, we can only
speculate on the outcome, which will probably also be very interesting from a
listeners point of view, since this method of synthesis will probably create entirely
new musical pieces (which might also sound just like noise).

## Data
The code comes with the sound textures used in Simoncelli’s experiment. These
sound textures include rain, fire, clapping, fan noise, and many other sound
textures. This is a sufficient base for sound textures.
To make the step between sound textures and musical piece, 2 albums of
Ambient and drone music were bought:

**-** Aphex Twin: Selected Ambient works


**-** Tim Hecker: An imaginary country
This slowly evolving music, which, in a way, ressembles to a musical evolving
noise, are a good starting point for our musical analysis.

All data is in the form of uncompressed .wav audio files, which work with the
algorithm.

## Subsequent steps
The next steps for our project are the following:

1. Modification of the code, to make it more dynamic and apt to work on more
    complex sounds
2. Processing of different sounds and pieces, experimenting with the algorithm
3. Preparation of the experiments, one on the perception of background noise
    and another on the preservation of certain musical aspects, which need to be
    defined


