# ardour_axiom49_midi_map

Ardour midi map for M-Audio Axiom 49

## Mapped functionality

- Playback controls are mapped to the keyboard.
- F/1-8 are mapped to the first 8 tracks.
- F9 is mapped to the master track.
- F/10-17 are mapped to mute the first 8 tracks.
- F18 is mapped to master mute.
- Rotary knobs E/1-8 are mapped to panning the first 8 tracks.

## Installation

Copy the file `M-Audio_Axiom49.map` to `~/.config/ardourX/midimap/` where X is the version of Ardour you are using.

e.g. for Ardour 8:

```bash
mkdir -p ~/.config/ardour8/midi_maps
cp M-Audio_Axiom49.map ~/.config/ardour8/midi_maps/
```

## Usage

Configure the keyboard as a control surface in Ardour:
From the menu select Edit->Preferences->Control Surfaces

- Enable 'Generic MIDI'
- Double click 'Generic MIDI'
- Select 'M-Audio Axiom 49' from the 'Incoming MIDI on' dropdown.
- Under 'MIDI bindings' select 'M-Audio Axiom 49' from the drodown.
