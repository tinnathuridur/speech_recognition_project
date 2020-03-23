Almenn framburðarorðabók fyrir talgreiningu ásamt útgáfu fyrir talgreini
==========================================================================
Date: August 18, 2017


Leyfi: CC BY 4.0

1) frambordabok_asr_v1.txt
--------------------------

Almenn íslensk framburðarorðabók byggð á orðabókinni sem gerð var fyrir Hjal verkefnið (sjá: "Framburðarorðabókin" á malfong.is).
Fjölmörgum orðum úr Íslenskum orðasjóði hefur verið bætt við og jafnframt var orðum úr upprunalega orðalistanum sleppt, ef þau fundust ekki í því úrtaki Orðasjóðsins sem unnið var með. Hljóðritanir voru að einhverju leyti leiðréttar, fyrst og fremst til þess að gæta samræmis og að þess væri gætt að einungis væru notuð tákn úr lokuðu setti IPA tákna (sjá lang_v1/phone_map.txt). Ný orð voru hljóðrituð með hjálp grapheme-to-phoneme algríms, sem þjálfað var á yfirförnu hljóðritununum. 

Form: hver lína inniheldur eitt orð, tab og hljóðritunina með bili á milli hverrar hljóðritunareiningar.

2) lang_v1
-----------

Mappan lang_v1 inniheldur öll skjöl sem nauðsynleg eru til þess að nota framburðarorðabókina (v1) í Kaldi talgreinisumhverfinu. Ef þjálfa á mállíkan sem nýtir orðalistann skal nota lang_v1/lm_vocab.txt.


Hafa samband:
-------------

Gögnin voru þróuð við Gervigreindarsetur Háskólans í Reykjavík.
Anna Björk Nikulásdóttir: annabn@ru.is
Jón Guðnason: jg@ru.is


General Icelandic pronunciation dictionary for ASR
==================================================

License: CC BY 4.0

1) fambordabod_asr_v1.txt
-------------------------

The general Icelandic pronunciation dicitonary for ASR is based on the Pronunciation dictionary developed for the "Hjal" project (see: Pronunciation dictionary at malfong.is). The original dictionary has been extended with words from the Málrómur corpus and from the Leipzig Wortschatz project. Transcription of new words was done automatically using a grapheme-to-phoneme algorithm.

Format: each line contains one word followed by a tab, and the transcription where each phoneme is separated by a space (aligned transcription).

2) lang_v1
----------

The lang_v1 directory contains all data necessary to use the pronunciation dictionary in the Kaldi toolkit. If you are training a language model using this dictionary, the clean vocabulary is in the file lang_v1/lm_vocab.txt


Contact:
--------

The data was developed at the Language and Voice Lab in the Reykjavik University (https://lvl.ru.is/).
Anna Björk Nikulásdóttir: annabn@ru.is
Jón Guðnason: jg@ru.is
