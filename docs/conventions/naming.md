# Object Number and File Name Conventions

Reference for assigning object numbers and filenames to time-based media
works and their digital derivatives.

!!! info "Acknowledgements"
    These guidelines have been continually updated since 2014. Contributors,
    past and present, in alphabetical order: Judith Andrews, Ina Archer,
    Jasmyn Castro, Chialin Chou, Walter Forsberg, Dan Finn, Emily Houf,
    AJ Lawrence, Bleakley McDowell, Bryan Miller, CK Ming, Emily Nabasny.
    Debt of inspiration to the NMAAHC cataloging team and to many other
    archives. Apologies to anyone we missed — send us your name.

## General formula

For a work on a single carrier:

```
2018.37.2.1a
[accessionYear].[collectionNumber].[workNumber].[instantiationNumber][componentElement]
```

For a work across multiple carriers:

```
2018.37.2.1a
2018.37.2.1b
[accessionYear].[collectionNumber].[workNumber].[instantiationNumber][componentElement]
```

Where:

- **Accession Year** — the year the collection was accessioned.
- **Collection Number** — the order the collection was accessioned in that year.
- **Work Number** — the work (or object) number within the accessioned collection. Works can only share work numbers when they're in the same collection.
- **Instantiation Number** — the instantiation of a work.
- **Component Element** — starts at `a` for the first physical carrier of the media essence. Additional carriers get consecutive letters (`b`, `c`, ...). Cans, cases, reels, and ephemera are numbered as accessories (`_acc1`, `_acc2`, ...) against their associated component element.

!!! note "Projection reels"
    For films to be projected (e.g. 35mm showprint collections), a reel
    number may be appended to the object number on the physical film
    head/tail leader and the film can(s) for projection-booth clarity:
    `R1` for reel 1, `R2` for reel 2, etc.

### Accessory numbering

The character `a` must be used for the first physical carrier of the essence
(videotape, audiotape, film). Subsequent letters are used for any remaining
physical carriers in the instantiation. Any containers, cans, cases, or other
ephemera related to a physical carrier are accessory components in TMS.

!!! note
    Accessory components in TMS are differentiated from "part of an object" components.

**Example:** a feature film in a can on one reel/core with Work Number
`2018.37.2`:

- The film: `2018.37.2.1a`
- The can: `2018.37.2.1a_acc1`
- The reel/core: `2018.37.2.1a_acc2`
- Additional ephemera (e.g. lab paper): `2018.37.2.1a_acc3` and so on

When an accessory is associated with more than one component element, both
letters appear. If a can with `_acc1` contains two reels (`2018.37.2.1a` and
`2018.37.2.1b`), the can's number is `2018.37.2.1ab_acc1`. Do **not** create
two object numbers (e.g. `2018.37.2.1a_acc1` and `2018.37.2.1b_acc1`) for a
single can.

!!! tip "Numerical order for accessories"
    Give `_acc1` to the accessory carrying the most metadata about the
    object — for films, usually the can/case. Reels/cores and other
    ephemera come after. Don't skip numbers.

### Filename convention

Filenames for digital files transform periods within the object number into
underscores, because periods can break automation and batch preservation
processes.

## Series numbering (mixed collections)

Mixed archival collections that contain time-based works (e.g. the Pearl
Bowser collection) get a **Series Number** inserted between the Collection
Number and Work Number, indicating the type of carrier:

| # | Media carrier |
| - | ------------- |
| 1 | Motion picture film (all gauges and bases) |
| 2 | Video — tape-based formats (cassette and open-reel) |
| 3 | Audio — tape-based formats (cassette and open-reel) |
| 4 | Optical discs (DVD, CD, Laserdisc, etc.) |
| 5 | Digital carriers (hard drives, thumb drives, computer disks, etc.) |
| 6 | Photographs (silver-based, other analog, printed digital) |
| 7 | Paper items (loose-leaf, flyers, posters) |
| 8 | Bound paper items (books, magazines) |
| 9 | Objects (furniture, trophies, clothing, other) |

!!! note
    The content of a digital carrier (e.g. digital photos, video, audio,
    software, documents) does not affect the numbering.

## Motion picture film

=== "A: one reel, one canister"

    One motion picture sound film on a metal projection reel, in a metal canister.

    **Naming pattern** — accession `2012.79.169`:

    - Film: `accessionYear(2012).collectionNumber(79).workNumber(169).instantiationNumber(1)componentElement(a)`
    - Metal canister: `..._acc1`
    - Metal projection reel: `..._acc2`
    - DPX package: `2012_79_169_1a_DPX.mkv`
    - Audio companion: `2012_79_169_1a_AUD.wav`
    - Access derivative: `2012_79_169_1a_DER_01.mp4` / `.mov`

    **Object numbers:**

    | Component | Object # |
    | --- | --- |
    | Film | `2012.79.169.1a` |
    | Metal canister | `2012.79.169.1a_acc1` |
    | Metal projection reel | `2012.79.169.1a_acc2` |
    | Lab paper in can | `2012.79.169.1a_acc3` |
    | DPX Package (ffv1/mkv) | `2012_79_169_1a.mkv` |
    | Audio file accompanying DPX Package | `2012_79_169_1a_AUD.wav` |
    | Access file(s) derived from DPX Package | `2012_79_169_1a_DER_01.mov` / `.mp4` |

=== "B: two reels, one canister"

    Two reels of sound 16mm film comprising one work, held on plastic cores
    inside a single 35mm metal canister.

    **Object numbers** — accession `2015.167.5`:

    | Component | Object # |
    | --- | --- |
    | Film (reel 1) | `2015.167.5.1a` |
    | Film (reel 2) | `2015.167.5.1b` |
    | Metal canister | `2015.167.5.1ab_acc1` |
    | Plastic core (reel 1) | `2015.167.5.1a_acc1` |
    | Plastic core (reel 2) | `2015.167.5.1b_acc1` |
    | DPX Package (reel 1) | `2015_167_5_1a.mkv` |
    | DPX Package (reel 2) | `2015_167_5_1b.mkv` |
    | Audio (reel 1) | `2015_167_5_1a_AUD.wav` |
    | Audio (reel 2) | `2015_167_5_1b_AUD.wav` |
    | Access derivatives (reels 1&2) | `2015_167_5_1ab_DER_01.mov` / `.mp4` * |

    !!! info "* Combined access files"
        NMAAHC policy combines access files across reels of a single work
        so the Smithsonian video player can stream efficiently.

    This schema extends to any number of reels in a single work: films
    get consecutive letters first; then canisters get `_acc1`, paper
    ephemera `_acc2`, and the cores `_acc3`.

=== "C: three works, one reel"

    One reel of 35mm film with three shorter works spliced together on the
    same metal reel inside one metal canister. All silent.

    **Option 1** — separate the works, give each its own work number:

    | Component | Object # |
    | --- | --- |
    | Film (work 1) | `2013.19.1.1a` |
    | Film (work 2) | `2013.19.2.1a` |
    | Film (work 3) | `2013.19.3.1a` |
    | Metal canister | `2013.19.1-3.1a_acc1` |
    | Metal reel | `2013.19.1-3.1a_acc2` |
    | DPX Package (work 1) | `2013_19_1_1a.mkv` |
    | DPX Package (work 2) | `2013_19_2_1b.mkv` |
    | DPX Package (work 3) | `2013_19_3_1c.mkv` |
    | Access derivatives | `2013_19_{1,2,3}_1a.mov` / `.mp4` |

    **Option 2** — splice all works with leader between them, treat as one reel:

    | Component | Object # |
    | --- | --- |
    | Film | `2013.19.1.1a` |
    | Metal canister | `2013.19.1.1a_acc1` |
    | Metal reel | `2013.19.1.1a_acc2` |
    | DPX Package | `2013_19_1_1a.mkv` |
    | Access derivative | `2013_19_1_1a.mov` / `.mp4` |

    !!! question "Which option?"
        Consider why the works are spliced together. Was it the filmmaker
        presenting a sample reel? A collector's organizational choice? Or
        just how it arrived from the lab? Pick whichever makes the archive
        more accessible and understandable.

=== "D: mixed rolls"

    Five smaller rolls of 16mm film on plastic cores, from an assortment of
    different works, grouped arbitrarily in the same 35mm metal canister.
    Some rolls are constituent reels of a single work; others aren't.

    Similar to Circumstance C, but with stronger reasons to separate
    constituent rolls into a new Work Number. If a copy already exists in
    the same collection, use a new Instantiation Number instead.

    For a great number of trims grouped together, combine them into a
    single reel with leader between them and either:

    - create a new instantiation with a single component letter, or
    - create a new instantiation where each trim gets its own component letter.

    Pick whichever fits the archive best given the number of trims.

=== "E: mixed archival collection"

    Mixed archival collections containing time-based media works (e.g.
    Pearl Bowser, `2012.79`) add a [Series Number](#series-numbering-mixed-collections)
    between the Collection Number and Work Number.

    Motion picture film in such a collection numbers as:

    ```
    2012.79.1.16.1a
    accessionYear(2012).collectionNumber(79).seriesNumber(1).workNumber(16).instantiationNumber(1)componentElement(a)
    ```

    The Pearl Bowser collection's time-based series:

    - `2012.79.1` — Motion Picture Films. Over 100 short- and feature-length films relating to the African American experience: home movies, TV documentaries, concert films, early 20th-century race films, outtake fragments, ephemera.
    - `2012.79.2` — Analog Videotapes. ~246 video recordings, including Pearl Bowser TV appearances, promotional spots, music videos, and SD telecine transfers of materials originating on film (many held in the collection's film series).
    - `2012.79.3` — Analog Audiotapes. ~213 audiocassettes of oral histories recorded by Pearl Bowser between 1972 and the early 1990s, as part of her Ford Foundation grant documenting African American filmmaking.

    **Example** — one 16mm reel in a metal can in the Bowser collection:

    | Component | Object # |
    | --- | --- |
    | Film | `2012.79.1.16.1a` |
    | Metal canister | `2012.79.1.16.1a_acc1` |
    | Metal projection reel | `2012.79.1.16.1a_acc2` |
    | Lab paper in can | `2012.79.1.16.1a_acc3` |
    | DPX Package (ffv1/mkv) | `2012_79_1_16_1a.mkv` |
    | Audio | `2012_79_1_16_1a_AUD.wav` |
    | Access derivative | `2012_79_1_16_1a_DER_01.mov` / `.mp4` |

## Videotape

=== "A: single U-matic"

    A single moving image work instantiated on a single 3/4-inch U-matic
    videotape, in a plastic case.

    **Object numbers** — accession `2015.66.1`:

    | Component | Object # |
    | --- | --- |
    | U-matic videotape cassette | `2015.66.1.1a` |
    | U-matic plastic case | `2015.66.1.1a_acc1` |
    | Preservation main file (ffv1/mkv) | `2015_66_1_1a.mkv` |
    | Access derivative | `2015_66_1_1a_DER_01.mov` / `.mp4` |

=== "B: multiple DigiBeta"

    A single moving image work instantiated across multiple DigiBeta tapes,
    each in its own plastic case.

    **Object numbers** — accession `2015.21.5`:

    | Component | Object # |
    | --- | --- |
    | DigiBeta tape 1 | `2015.21.5.1a` |
    | DigiBeta tape 2 | `2015.21.5.1b` |
    | DigiBeta case (tape 1) | `2015.21.5.1a_acc1` |
    | DigiBeta case (tape 2) | `2015.21.5.1b_acc1` |
    | Preservation main file (tape 1) | `2015_21_5_1a_PM.mkv` |
    | Preservation main file (tape 2) | `2015_21_5_1b_PM.mkv` |
    | Access derivatives (tapes 1&2) | `2015_21_5_1ab_DER_01.mov` / `.mp4` * |

    !!! info "* Combined access files"
        NMAAHC policy combines access files across tapes for a single work
        so Smithsonian video player streaming is efficient.

=== "C: one VHS, three works"

    One VHS videotape with three shorter works recorded on it, inside one
    plastic case, with a notecard also in the case.

    Unlike film, the archivist does **not** separate works during numbering.
    The tape and its preservation file are treated as one object. Access
    derivatives (`DER_02`, `DER_03`, etc.) can be created as segments of
    the whole tape.

    | Component | Object # |
    | --- | --- |
    | VHS videotape | `2013.19.1.1a` |
    | VHS plastic case | `2013.19.1.1a_acc1` |
    | Notecard inside case | `2013.19.1.1a_acc2` |
    | Preservation main file | `2013_19_1_1a.mkv` |
    | Access derivative (segment 1) | `2013_19_1_1a_DER_01.mov` / `.mp4` |
    | Access derivative (segment 2) | `2013_19_1_1a_DER_02.mov` / `.mp4` |
    | Access derivative (segment 3) | `2013_19_1_1a_DER_03.mov` / `.mp4` |

=== "D: mixed rolls"

    Five smaller rolls of 16mm film on plastic cores, from an assortment of
    different works, grouped arbitrarily in the same 35mm metal canister.
    Some rolls are constituent reels of a single work; others aren't.

    Similar to Circumstance C, but with stronger reasons to separate
    constituent rolls into a new Work Number. If a copy already exists in
    the same collection, use a new Instantiation Number instead.

    For many trims grouped together, combine them on a single reel with
    leader between them and either create a new instantiation with one
    component letter, or give each trim its own component letter —
    whichever fits the archive better.

=== "E: mixed archival collection"

    Mixed archival collections containing time-based media add a
    [Series Number](#series-numbering-mixed-collections) between the
    Collection Number and Work Number (same principle as Motion picture /
    Circumstance E).

    **Example** — one 16mm reel in the Bowser collection:

    | Component | Object # |
    | --- | --- |
    | Film | `2012.79.1.16.1a` |
    | Metal canister | `2012.79.1.16.1a_acc1` |
    | Metal projection reel | `2012.79.1.16.1a_acc2` |
    | Lab paper in can | `2012.79.1.16.1a_acc3` |
    | DPX Package (ffv1/mkv) | `2012_79_1_16_1a.mkv` |
    | Audio | `2012_79_1_16_1a_AUD.wav` |
    | Access derivative | `2012_79_1_16_1a_DER_01.mov` / `.mp4` |

---

!!! note "Living document"
    Given the variety of media objects across the Museum's time-based
    collections of film, video, audio, and digital, this process of naming
    and numbering can't be formulated for every possible situation. These
    guidelines are intended to evolve.
