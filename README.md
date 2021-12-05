quick fix that I made for IDEA 21.2.3 , didn't make it. Plugin still was having problems annnnnnnt completely stopped working for IDEA 21.3. So, I recreated it using new JB API, you can find result here https://github.com/psyrtsov/jetal
and get deployable zip here https://github.com/psyrtsov/jetal/releases/tag/tag0.1

sorry i don't have time and IDEA plugin API expierencen to make it properly in this fork.

# IntelliJ support for VoiceCode (IDE plugin)

This adds [VoiceCode](https://voicecode.io) support for IntelliJ, in tandem with [this VoiceCode package](https://github.com/anonfunc/voicecode-intellij).

This should support:

- Android Studio
- AppCode
- CLion
- DataGrip
- GoLand
- MPS
- PhpStorm
- PyCharm (Professional and Community editions)
- RubyMine
- WebStorm

However, my primary use case is currently Java and IntelliJ CE.  I will not be able to debug or reproduce issues occuring outside of the freely available IDEs.  (Pull requests are welcome. :smile:)  Support for these IDEs is contingent on their menu items remaining very similar, see *Limitations*.

## Manual Installation

### Download release zip, install plugin from zip.

## Testing uncommitted changes

    ./gradlew runIde