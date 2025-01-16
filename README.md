# Multi-CAST Mandarin

## How to cite

If you use these data please cite
- the original source
  > Vollmer, Maria. 2021. Multi-CAST Mandarin. In Haig, Geoffrey & Schnell, Stefan (eds.), Multi-CAST: Multilingual corpus of annotated spoken texts. Version 2101. Bamberg: University of Bamberg. (multicast.aspra.uni-bamberg.de/#mandarin) (date accessed)
- the derived dataset using the DOI of the [particular released version](../../releases/) you were using

![](cldf/media/image.jpg)

## Description


The Multi-CAST **Mandarin** (Modern Standard Mandarin; [mand1415](https://glottolog.org/resource/languoid/id/mand1415)) corpus consists of traditional narratives from three native speakers of Mandarin. They were recorded in Xī'ān, PRC, by Maria Vollmer during an exchange semester in 2015 and 2016. Two of the speakers are originally from Northeast China (Dōngběi), the third hails from Xī'ān.

The stories were transcribed by Liu Ruoyu in 2016 and 2017 under the supervision of Maria Vollmer, and subsequently translated, glossed, and annotated with GRAID between 2016 and 2019 by Maria Vollmer. Annotations with RefIND and ISNRef were added by Maria Vollmer and Adrian Kuqi in 2019. Further stories have been recorded and transcribed and will be added to the corpus in the future.

This dataset is licensed under a CC-BY-4.0 license

Available online at https://multicast.aspra.uni-bamberg.de/#mandarin


```geojson
{
    "type": "FeatureCollection",
    "features": [
        {
            "type": "Feature",
            "geometry": {
                "type": "Point",
                "coordinates": [
                    116.228,
                    40.0209
                ]
            }
        },
        {
            "type": "Feature",
            "geometry": {
                "type": "Polygon",
                "coordinates": [
                    [
                        [
                            111.228,
                            45.0209
                        ],
                        [
                            121.228,
                            45.0209
                        ],
                        [
                            121.228,
                            35.0209
                        ],
                        [
                            111.228,
                            35.0209
                        ],
                        [
                            111.228,
                            45.0209
                        ]
                    ]
                ]
            }
        }
    ]
}
```



## Corpus counts

Only a small number of basic GRAID symbols are counted:

*Function symbols*
- ⟨0⟩ zero
- ⟨pro⟩ definite pronoun
- ⟨np⟩ full noun phrase
- ⟨other⟩ form not further specified

*Person/Animacy symbols*
- ⟨.1⟩ first person
- ⟨.2⟩ second person
- ⟨.h⟩ third person, human
- ⟨.d⟩ third person, anthropomorphic
- ø third person, non-human

*Function symbols*
- ⟨:s⟩ subject of an intransitive clause
- ⟨:a⟩ subject of a transitive clause
- ⟨:ncs⟩ non-canonical subject
- ⟨:p⟩ direct object
- ⟨:obl⟩ oblique argument
- ⟨:g⟩ goal argument
- ⟨:l⟩ locational argument
- ⟨:pred⟩ predicate
- ⟨:poss⟩ possessive
- ⟨:other⟩ function not further specified

Only basic categories are listed; categories represented by complex symbols with additional
specifiers (e.g. ⟨dem_pro⟩ ‘demonstrative pronoun’) have been subsumed under the more basic
category (e.g. ⟨pro⟩ ‘definite pronoun’). Please refer to the annotation notes for this corpus for
information on all annotated categories, including those not listed here.

| GRAID | ⟨:s⟩ | ⟨:a⟩ | ⟨:ncs⟩ | ⟨:p⟩ | ⟨:obl⟩ | ⟨:g⟩ | ⟨:l⟩ | ⟨:pred⟩ | ⟨:poss⟩ | ⟨:other⟩ | totals |
|:--------------|-------:|-------:|---------:|-------:|---------:|-------:|-------:|----------:|----------:|-----------:|---------:|
| **⟨0.1⟩** | 30 | 48 | 0 | 2 | 3 | 0 | 0 | 0 | 0 | 0 | 83 |
| **⟨0.2⟩** | 18 | 24 | 0 | 0 | 1 | 0 | 0 | 0 | 0 | 0 | 43 |
| **⟨0.h⟩** | 223 | 205 | 0 | 28 | 0 | 2 | 0 | 0 | 0 | 0 | 458 |
| **⟨0.d⟩** | 1 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1 |
| **⟨0⟩** | 47 | 11 | 0 | 72 | 2 | 0 | 0 | 0 | 0 | 0 | 132 |
| **⟨pro.1⟩** | 20 | 29 | 0 | 7 | 5 | 3 | 0 | 0 | 20 | 2 | 86 |
| **⟨pro.2⟩** | 20 | 23 | 0 | 6 | 5 | 4 | 0 | 0 | 5 | 0 | 63 |
| **⟨pro.h⟩** | 50 | 48 | 0 | 14 | 11 | 0 | 0 | 0 | 37 | 1 | 161 |
| **⟨pro.d⟩** | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| **⟨pro⟩** | 20 | 4 | 0 | 7 | 3 | 1 | 6 | 0 | 0 | 3 | 44 |
| **⟨np.1⟩** | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| **⟨np.2⟩** | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| **⟨np.h⟩** | 146 | 72 | 0 | 84 | 48 | 13 | 0 | 27 | 39 | 1 | 430 |
| **⟨np.d⟩** | 0 | 0 | 0 | 1 | 0 | 0 | 0 | 0 | 0 | 0 | 1 |
| **⟨np⟩** | 102 | 9 | 0 | 227 | 52 | 16 | 86 | 48 | 16 | 156 | 712 |
| **⟨other.1⟩** | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| **⟨other.2⟩** | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| **⟨other.h⟩** | 0 | 1 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1 |
| **⟨other.d⟩** | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| **⟨other⟩** | 3 | 0 | 0 | 12 | 1 | 3 | 1 | 156 | 0 | 0 | 176 |
| | 680 | 474 | 0 | 460 | 131 | 42 | 93 | 231 | 117 | 163 | 2391 |


**Clause boundaries**

| GRAID | count |
|:-----------|--------:|
| **⟨##⟩** | 1111 |
| **⟨#⟩** | 83 |
| **totals** | 1194 |



## Corpus metadata

- [Annotation notes](cldf/media/annotation-notes.pdf)
- [Translated texts](cldf/media/translated-texts.pdf)


## CLDF Datasets

The following CLDF datasets are available in [cldf](cldf):

- CLDF [TextCorpus](https://github.com/cldf/cldf/tree/master/modules/TextCorpus) at [cldf/TextCorpus-metadata.json](cldf/TextCorpus-metadata.json)