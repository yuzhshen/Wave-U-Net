3-28
- Added TensorBoard audio code
- Audio doesn't save at downsampled bitrate?
    - Rogue `rate` variable :(
    - Fixed now, but have to retrain
- Difference layer not used - just indepdendent tanh activations
    - Option for using difference layer is available
