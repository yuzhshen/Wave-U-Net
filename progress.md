3-28
- Audio doesn't save at downsampled bitrate?
    - Rogue `rate` variable :(
    - Fixed now, but have to retrain
- Difference layer not used - just indepdendent tanh activations
    - Option for using difference layer is available
- Changed `num_snippets_per_track` to 50 from 100
- Added TensorBoard audio code
    - Tweaked to save at dev/test time only