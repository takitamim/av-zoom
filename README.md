# Audio-Visual Zooming — Beamforming Experiments

A collaborative research fork of **[Hasibujjaman/av-zoom](https://github.com/Hasibujjaman/av-zoom)**. Original authorship and fork provenance are retained.

## Start here

- `audio/beamforming/Taki/`: multichannel simulation, mixture generation, STFT/ISTFT, steering vectors and MVDR work.
- `audio/beamforming/COMPARISONS & TESTS/`: comparison, listening and numerical checks.
- `audio/beamforming/Dataset Generation/`: mixture-generation experiments.
- `audio/beamforming/Metrics/`: SI-SDR and output-SINR helpers.
- `FIGURES/`: research figures.

## Running an experiment

Open the repository in MATLAB, navigate to the script’s working directory and inspect its configuration before running it. Scripts reference local audio inputs and may require MATLAB signal/audio processing functions. For example, `Taki/dataset_final.m` expects named clean-speech and interference files in its working directory; supply those assets first.

There is no single verified end-to-end launcher or declared toolbox/version matrix. Preserve the current experiment directories: several scripts use relative paths. Generated audio and intermediate artifacts are historical research assets, not evidence of an independently reproduced benchmark.

## Attribution

This fork is showcased as collaborative work. It is distinct from the standalone CRN speech-enhancement project described in my résumé. Do not remove original collaborator credit when reusing results.
