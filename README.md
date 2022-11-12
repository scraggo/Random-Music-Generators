# Random-Music-Generators

<https://random-music-generators.herokuapp.com>

## Documentation

- [About](docs/about.md)
- [Accounts](docs/accounts.md)
- [Melody Generators](docs/melody.md)
- [Rhythm Generators](docs/rhythm.md)
- [Chord Progression Generators](docs/chord-progression.md)

## Overview

Generate unlimited unique melodies, rhythms, and chord progressions with easily changed parameters including tonality, rhythm, and interval jumps.

These melodies can be previewed in-browser and downloaded as MIDI. (These MIDIs can be used in any DAW for manipulation.)

### Philosophy

1. **Random is better than patterned.** The goal of this project is to create **random** music. The sounds created are often off-kilter and "computery", but creating "normal" sounding ideas with this tool is perfectly possible and not discouraged.

The aesthetic motivation behind this project is to break free of existing patterns in the service of _hearing and creating something new_. The project makes heavy use of random number generating functions to defy predictibility. Machine-learning algorithms (which analyze existing music), are currently not used, and would only be added in service to randomness.

2\. **Use the ideas to break out of your musical ruts.** If you've been composing for a while, you may notice that you tend to write similar sounding ideas from song to song, section to section. Given the flexibility of this tool, you can decide where you'd like to inject new parameters into your compositional style.

3\. **Inexperienced and experienced composers alike can use this tool as a place to start for writing music in a zero-pressure way.** Having absolutely random notes generated takes away the cognitive load when you'd like to write, but don't know where to begin. If you were to import one of the MIDIs into a DAW or write one down on manuscript paper, they can be used verbatim or edited to your heart's content. Maybe you'll be inspired to come up with something amazing with randomly generated music!

4\. **Find presets to generate new ideas with similar settings.** This is best explained with an example: The default melody preset is a mid-range, generic set of notes. If you were to change 'Tonality Options' to 'Chromatic', 'Note Durations' to 'Sixteenth Note', 'Note Range' to 'G2 G4', 'No of Notes' to 13, 14, 15, or 16, you can instantly generate as many creepy, cave, video-gamey boss music ideas as you wish.

## Technology

- [React](https://reactjs.org/)
- [Redux](https://redux.js.org/)
- [Semantic UI React](https://react.semantic-ui.com/)
- [MidiWriterJS](https://github.com/grimmdude/MidiWriterJS)
- [ToneJS](https://github.com/Tonejs/Tone.js)
- [tone-rhythm](https://github.com/scraggo/tone-rhythm)
- [tonal](https://github.com/danigb/tonal)
- [sharp11](https://github.com/jsrmath/sharp11)
- [webaudio-tinysynth](https://github.com/g200kg/webaudio-tinysynth)

## Videos

- [Random Melody Generator - Overview / New Look - YouTube](https://www.youtube.com/watch?v=D46ujdZg4o0)
- [Random Melody Generator - Tutorial - YouTube](https://www.youtube.com/watch?v=ygfC9vkTKPw&t=1s)

## Posts

<https://www.scraggo.com/tags/random-music-generators/>

Community Posts:

- [Random Music Generators is great for ear training - Vinnie Classroom](https://www.vinnieclassroom.com/2022/02/27/random-music-note-generator/)

## Contact

Suggest features, file support issues, or get in touch for any reason:

<https://www.scraggo.com/contact/>

## Legal

- [COPYRIGHT.md](COPYRIGHT.md)
- [TERMS_OF_USE.md](TERMS_OF_USE.md)
