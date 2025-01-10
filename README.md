# th.speech

[![](https://img.shields.io/static/v1?label=Support%20on%20Ko-Fi&message=%E2%9D%A4&logo=Kofi)](https://ko-fi.com/I2I3SV7FX)
[![](https://img.shields.io/static/v1?label=Support%20on%20Patreon&message=%E2%9D%A4&logo=Patreon)](https://www.patreon.com/bePatron?u=9649817)

## About 

Use the 'say' command from the terminal on Mac in your Max8 or Max9 patch, through the `[shell]` object by Jeremy Bernstein. Specify the voice, volume and speech rate. Inspired by `[aka.speech]` to work as an alternative, since that object doesn't work on arm64.

## Install

Download and install the shell external by Jeremy Bernstein here:

- https://github.com/jeremybernstein/shell/releases/tag/1.0b3

Download the ZIP

```
1. unzip and place in Max Searchpath (eg. ~/Documents/Max 8/Library)
```

Or through clone

```
1. $ cd ~/Documents/Max\ 8/Library
2. $ git clone https://github.com/tmhglnd/th.speech.git
```

```
3. restart Max8/9
4. Create New Patcher
5. New object [th.speech] > Open helpfile
```

## Sources

- https://github.com/akamatsu/aka.speech
- https://developer.apple.com/library/archive/documentation/UserExperience/Conceptual/SpeechSynthesisProgrammingGuide/FineTuning/FineTuning.html

## Limitations

Not supported yet, but on the to-do list:

- speech pitch
- speech modulation
- inputMode (text/phonomes)
- characterMode (normal/literal)
- numberMode (normal/literal)

## License

The MIT License

