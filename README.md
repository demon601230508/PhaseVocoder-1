# PhaseVocoder
A Phase Vocoder implementation in C

```
  synth_ph[freq_bin] = fmod(synth_ph[freq_bin]+(next_phase[freq_bin]-prev_phase[freq_bin])*ts_factor, 2.0*PI);
  ```
