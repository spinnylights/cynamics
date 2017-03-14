# Cynamics

Cynamics is a library for generating "human" dynamics from dynamics markings, similar to the functionality that exists in some commercial notation programs like [Sibelius](http://www.avid.com/en/sibelius) or [Finale](http://www.finalemusic.com/). You can specify markings like "mf" or "p" for each note, and use this library to produce natural-sounding loudness contours from them. The open-source tools that exist to facilitate this currently (such as [MuseScore](https://musescore.org/) or [LilyPond](http://lilypond.org/)) apply "flat" dynamics (say a MIDI velocity of 84 for every "mf" marking), so this library is inteded to fill a gap in the open source space.

Currently development is focused on use with [Csound](http://csound.github.io/). However, I don't think it would be terribly difficult to use the library in other contexts. If you're trying to use it with something else and running into trouble, feel free to make a feature request on the issues page, or submit a pull request with the changes or additional features you need.

## Contributing

Pull requests are very welcome! There are just two points to keep in mind:

  * Please ensure that any additions or modifications you make to the public API are covered by unit tests. If you add entirely new features, please also include acceptance/end-to-end tests for each. This project uses [PyTest](http://docs.pytest.org/en/latest/) for everything. If you're having trouble with this, let me know and I can help you out.
  * Please follow the [Contributor Covenenant](http://contributor-covenant.org/version/1/4/) in your interactions with me or anyone else on the project. Be nice, basically.
