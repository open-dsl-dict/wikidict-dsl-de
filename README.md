# wikidict-dsl-de - Wikidata Bilingual DSL Dictionaries (German)

This repository makes available a collection of bilingual German dictionaries in DSL format derived from interwiki links (links between article titles in different languages) in Wikipedia. The data has been extracted from [Wikidata](https://www.wikidata.org/).

## Format

ABBYY Lingvo DSL is a flexible dictionary format that can be read by dictionary applications such as [Goldendict](https://github.com/goldendict/goldendict) and converted to other formats using tools such as [pyglossary](https://github.com/ilius/pyglossary). There are also a number of tools for creating DSL format dictionaries available in the [dsl-tools](https://github.com/dohliam/dsl-tools) project.

DSL files *must* be saved as UTF-16 to be usable by dictionary programs. The raw source files in this repository are saved in UTF-8 format, which is both significantly smaller in terms of file size, and also readable (and diffable) by git. However, there are fully encoded and compressed `.dsl.dz` dictionaries ready for use available in the [Releases](https://github.com/open-dsl-dict/wikidict-dsl-de/releases) section.

You can also use the `rezip_dsl.rb` and `unzip_dsl.rb` [scripts](https://github.com/dohliam/dsl-tools/tree/master/zip_unzip) provided by the [dsl-tools](https://github.com/dohliam/dsl-tools) repo to encode/compress and decode/uncompress the dictionaries either individually or as a group.

## Data

The data directory contains the bilingual dictionaries in pairs according to [ISO language code](http://en.wikipedia.org/wiki/ISO_639-1).

The basic filename pattern is `[ISO]-de_wikidict.dsl`, with `[ISO]` being the source language ISO code. A list of all language pairs is [below](#available-language-pairs).

## Available language pairs

Language codes | Language names
-------------- | --------------
`af-de` | Afrikaans => German
`am-de` | Amharic => German
`ang-de` | Anglo-Saxon => German
`ar-de` | Arabic => German
`arc-de` | Aramaic => German
`bg-de` | Bulgarian => German
`bi-de` | Bislama => German
`bn-de` | Bengali => German
`bo-de` | Tibetan => German
`br-de` | Breton => German
`bs-de` | Bosnian => German
`ca-de` | Catalan => German
`cdo-de` | Min Dong => German
`chr-de` | Cherokee => German
`chy-de` | Cheyenne => German
`cr-de` | Cree => German
`cs-de` | Czech => German
`cy-de` | Welsh => German
`da-de` | Danish => German
`el-de` | Greek => German
`en-de` | English => German
`eo-de` | Esperanto => German
`es-de` | Spanish => German
`et-de` | Estonian => German
`eu-de` | Basque => German
`fa-de` | Persian => German
`ff-de` | Fula => German
`fi-de` | Finnish => German
`fr-de` | French => German
`ga-de` | Irish => German
`gan-de` | Gan => German
`gd-de` | Scottish Gaelic => German
`gu-de` | Gujarati => German
`gv-de` | Manx => German
`ha-de` | Hausa => German
`hak-de` | Hakka => German
`haw-de` | Hawaiian => German
`he-de` | Hebrew => German
`hi-de` | Hindi => German
`hr-de` | Croatian => German
`ht-de` | Haitian => German
`hu-de` | Hungarian => German
`hy-de` | Armenian => German
`id-de` | Indonesian => German
`ig-de` | Igbo => German
`is-de` | Icelandic => German
`it-de` | Italian => German
`iu-de` | Inuktitut => German
`ja-de` | Japanese => German
`jbo-de` | Lojban => German
`jv-de` | Javanese => German
`ka-de` | Georgian => German
`kg-de` | Kongo => German
`ki-de` | Kikuyu => German
`kl-de` | Greenlandic => German
`km-de` | Khmer => German
`ko-de` | Korean => German
`la-de` | Latin => German
`lg-de` | Luganda => German
`lo-de` | Lao => German
`lt-de` | Lithuanian => German
`lv-de` | Latvian => German
`mg-de` | Malagasy => German
`mi-de` | Maori => German
`mn-de` | Mongolian => German
`ms-de` | Malay => German
`mt-de` | Maltese => German
`nah-de` | Nahuatl => German
`ne-de` | Nepali => German
`nl-de` | Dutch => German
`nn-de` | Norwegian (Nynorsk) => German
`no-de` | Norwegian => German
`nv-de` | Navajo => German
`ny-de` | Chichewa => German
`oc-de` | Occitan => German
`pa-de` | Punjabi => German
`pi-de` | Pali => German
`pl-de` | Polish => German
`ps-de` | Pashto => German
`pt-de` | Portuguese => German
`qu-de` | Quechua => German
`ro-de` | Romanian => German
`ru-de` | Russian => German
`sa-de` | Sanskrit => German
`se-de` | Northern Sami => German
`sh-de` | Serbo-Croatian => German
`sk-de` | Slovak => German
`sl-de` | Slovenian => German
`sn-de` | Shona => German
`so-de` | Somali => German
`sq-de` | Albanian => German
`sr-de` | Serbian => German
`sv-de` | Swedish => German
`sw-de` | Kiswahili => German
`ta-de` | Tamil => German
`te-de` | Telugu => German
`th-de` | Thai => German
`tl-de` | Tagalog => German
`tpi-de` | Tok Pisin => German
`tr-de` | Turkish => German
`ug-de` | Uyghur => German
`uk-de` | Ukrainian => German
`ur-de` | Urdu => German
`vi-de` | Vietnamese => German
`wo-de` | Wolof => German
`wuu-de` | Wu => German
`xh-de` | Xhosa => German
`yi-de` | Yiddish => German
`yo-de` | Yoruba => German
`za-de` | Zhuang => German
`zh-de` | Chinese (Mandarin) => German
`zh_classical-de` | Classical Chinese => German
`zh_min_nan-de` | Min Nan => German
`zh_yue-de` | Cantonese => German
`zu-de` | Zulu => German

## Statistics

### Dictionary size

Language pair | # of entries
------------- | ------------
`af-de` | 24323
`am-de` | 5713
`ang-de` | 2270
`ar-de` | 125872
`arc-de` | 1317
`bg-de` | 104888
`bi-de` | 416
`bn-de` | 18683
`bo-de` | 2576
`br-de` | 34471
`bs-de` | 28369
`ca-de` | 196465
`cdo-de` | 2011
`chr-de` | 445
`chy-de` | 591
`cr-de` | 96
`cs-de` | 176311
`cy-de` | 27931
`da-de` | 113279
`el-de` | 59332
`en-de` | 907968
`eo-de` | 128123
`es-de` | 397319
`et-de` | 67434
`eu-de` | 84278
`fa-de` | 168044
`ff-de` | 180
`fi-de` | 196689
`fr-de` | 594420
`ga-de` | 21257
`gan-de` | 4630
`gd-de` | 11189
`gu-de` | 3424
`gv-de` | 4013
`ha-de` | 386
`hak-de` | 2796
`haw-de` | 809
`he-de` | 99756
`hi-de` | 24384
`hr-de` | 70506
`ht-de` | 13692
`hu-de` | 138127
`hy-de` | 46314
`id-de` | 100109
`ig-de` | 719
`is-de` | 23583
`it-de` | 476531
`iu-de` | 348
`ja-de` | 260821
`jbo-de` | 1133
`jv-de` | 15616
`ka-de` | 46949
`kg-de` | 649
`ki-de` | 283
`kl-de` | 1541
`km-de` | 1529
`ko-de` | 132923
`la-de` | 75944
`lg-de` | 123
`lo-de` | 1063
`lt-de` | 78002
`lv-de` | 39359
`mg-de` | 33821
`mi-de` | 2230
`mn-de` | 10382
`ms-de` | 88736
`mt-de` | 2331
`nah-de` | 6799
`ne-de` | 6802
`nl-de` | 407114
`nn-de` | 59092
`no-de` | 191543
`nv-de` | 1721
`ny-de` | 129
`oc-de` | 48294
`pa-de` | 8099
`pi-de` | 2189
`pl-de` | 423984
`ps-de` | 2598
`pt-de` | 333106
`qu-de` | 11942
`ro-de` | 130437
`ru-de` | 419706
`sa-de` | 4576
`se-de` | 5629
`sh-de` | 112183
`sk-de` | 108513
`sl-de` | 60726
`sn-de` | 1502
`so-de` | 2380
`sq-de` | 28695
`sr-de` | 129341
`sv-de` | 302847
`sw-de` | 18120
`ta-de` | 22413
`te-de` | 7743
`th-de` | 48183
`tl-de` | 33905
`tpi-de` | 915
`tr-de` | 114769
`ug-de` | 2185
`uk-de` | 206594
`ur-de` | 26818
`vi-de` | 153540
`wo-de` | 889
`wuu-de` | 2241
`xh-de` | 265
`yi-de` | 7269
`yo-de` | 17175
`za-de` | 474
`zh-de` | 242455
`zh_classical-de` | 2378
`zh_min_nan-de` | 10049
`zh_yue-de` | 17358
`zu-de` | 575

### Top ten dictionaries by number of entries

Language pair | # of entries
------------- | ------------
`en-de` | 907968
`fr-de` | 594420
`it-de` | 476531
`pl-de` | 423984
`ru-de` | 419706
`nl-de` | 407114
`es-de` | 397319
`pt-de` | 333106
`sv-de` | 302847
`ja-de` | 260821

## License

According to the Wikidata website:

> All structured data from the main and property namespace is available under the Creative Commons CC0 License

The data in this repository is therefore made available under the same [Creative Commons CC0 License](https://creativecommons.org/publicdomain/zero/1.0/) as that used by the Wikidata project. All of the data has been derived from the Wikidata JSON format [database dumps](https://dumps.wikimedia.org/wikidatawiki/entities/).
