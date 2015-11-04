# saturation-ssvep
Scripts to measure the SSVEP response to stimuli of varying contrast

Runs through a few "training" trials (demos), then runs randomised ssvep trials of different contrasts.

- Specify the desired contrast by editing `contrasts`
- Specify trial number & length by editing `nrep` and `trialdur`
- Change the target frequency by adjusting `t_frames` (achieved frequency will be your monitor frequency/`t_frames`)
- Change stimulus size and spatial frequency by adjusting `stimsize` and `cycperdeg`

To make sure the computer is sending the right triggers to your EEG setup, make sure to take a look at any line containing the function `outp`
