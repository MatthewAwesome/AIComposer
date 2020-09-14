# AIComposer
An AI Composer tool packaged as a .ipynb file. 

## Running the Project:
The associated Notebook is best opened and ran in GoogleColab. 

## Prerequisites: 
To maximize your fun you'll probably want MIDI files to serve as input. [You can download a bunch of MIDI files here](https://colinraffel.com/projects/lmd/#get).

## Known Issues: 
Not all MIDI files work. To work with the provided models, the MIDI files need to be such that 16 bar trios can be extracted from the inputted MIDIs. MIDI files from which trios cannot be extracted break of the pipeline so to speak. Apologies for the inconvenience, I may ask the Magenta team about this.

## References: 
[Dinculescu, M., Engel, J., & Roberts, A. (2019). MidiMe: Personalizing a MusicVAE model with user data.](https://research.google/pubs/pub48628/)
[Raffel, C. “Learning-Based Methods for Comparing Sequences, with Applications to Audio-to-MIDI Alignment and Matching”. PhD Thesis, 2016.](https://colinraffel.com/publications/thesis.pdf)
