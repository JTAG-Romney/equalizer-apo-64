# EqualizerAPO - 64bit port

This repo contains a 64-bit port of [EqualizerAPO](https://sourceforge.net/p/equalizerapo/) - system wide equalizer for Windows.
Standard Equalizer APO performs all sound processing using 32-bit float number. This is a modification of the processing engine 
that uses 64-bit double precision numbers instead. This increases fidelity especially with complex configuration files (like configurations 
generated by [HeSuVi](/https://sourceforge.net/projects/hesuvi/)).

No functionality was added or modified. The source code is based on commit *r73* of the original repo.

## Installation

1. You will need standard Equalizer APO installed on your system.
2. Disable Equalizer APO for all audio devices.
3. Reboot your computer.
4. Unpack the [attached zip archive](https://github.com/chebum/equalizer-apo-64/releases/) into the Equalizer APO installation folder. Replace EqualizerAPO.dll. Please backup the original file before doing this.
5. Re-enable Equalizer APO and reboot. This will load modified 64-bit audio processing engine.

## Uninstallation

1. Disable Equalzier APO for all audio devices.
2. Reboot your computer.
3. Replace the EqualizerAPO.dll with the original backup you created when installing 64-bit version.
4. Re-enable Equalizer APO and reboot.
