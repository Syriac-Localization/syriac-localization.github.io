# Allowable Characters

In an effort to come up with the most universal set of standardized words between Western and Assyrian readers and speakers, we should limit ourselves to characters in the Syriac character set that are shared between readers of both scripts for the purposes of Unicode CLDR:

    All standard characters in U+0710 SYRIAC LETTER ALAPH through U+072C SYRIAC LETTER TAW excluding the Garshuni characters [U+0727 SYRIAC LETTER REVERSED PE, U+071C SYRIAC LETTER TETH GARSHUNI, U+0714 SYRIAC LETTER GAMAL GARSHUNI]
    U+0308 COMBINING DIAERESIS - [ ̈ ] Syameh above (for pluralizations) - Note, Eastern does not use the below version. The above version is universal in this respect.
    U+0323 COMBINING DOT BELOW - [ ̣ ] for words like ܡ̣ܢ min
    U+0330 COMBINING TILDE BELOW - [ ̰ ] Majleana below
    U+0303 COMBINING TILDE -[ ̃ ] Majleana above
    U+0307 COMBINING DOT ABOVE - [ ̇ ] for feminizations like in ܗ̇ܝ as well as ܡ̇ܢ man
    U+0747 SYRIAC OBLIQUE LINE ABOVE - [ ݇ ] Talqana - Note, Eastern does not use the below version making this one the more universal one
    U+0742 SYRIAC RUKKAKHA - [ ݂ ] Note, this should be used over U+032E COMBINING BREVE BELOW under Peh since Western Assyrian does not use this character under Peh
    U+0741 SYRIAC QUSHSHAYA - [ ݁ ]
    U+070F SYRIAC ABBREVIATION MARK - e.g. ܬܫܒܘܚܬܐ --> ܬ܏ܫܒܘ -- also for numbers
    U+070A SYRIAC CONTRACTION - ܩܫ܊ <-- ܩܫܐ
    U+060C ARABIC COMMA
    U+061B ARABIC SEMICOLON
    U+061F ARABIC QUESTION MARK
    U+0640 ARABIC TATWEEL

Note that this list excludes all vowel diacritics from both scripts

For arithmetic operators, we should use the non-Arabic mathematical operators as does most of the world.
