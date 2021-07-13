# Bach Chorales Multiple Chord Labels (BCMCL) dataset
The Bach Chorales Multiple Chord Labels dataset was proposed in our DLfM (Digital Library for Musicology) 2020 conference paper: "Automatic Chord Labelling: A Figured Bass Approach". There are four parallel tracks of chord labels, produced by each of the four rule-based algorithms (Algorithms A, B, C, and D). The chord labels of each algorithm can be found in each folder, where the music (Bach chorales) and annotations are presented in the MusicXML format. Overall, there are 120 Bach chorales (or 123 since there are three chorales with two versions) annotated this way.

BCMCL is now archived at [Zenodo](https://zenodo.org/record/5068319#.YO4oEzPiuHs).

A sample example produced by Algorithm D is shown below: Measures 7 through 9 of BWV 33.06 “Allein zu dir, Herr Jesu Christ”. We artificially added the final bottom staff, which collapses all sonorities into one octave to more directly reveal the pitch-class content. There are three annotations added underneath this bottom staff: (1) the original figured bass annotations (FBAs) from the [BCFB](https://github.com/juyaolongpaul/Bach_chorale_FB) dataset, (2) the figure(s) whose corresponding pitch class is not found in the musical surface, and (3) the translated chord labels (by Algorithm D in this example). Take the fist slice of Measure 7 as an example (m. 7.1): "6/5" are the original FBAs from BCFB, '6' means that the corresponding pitch class "B" of this figure '6' is not found in the musical surface. "B/o7" and "Dm7" are two alternative chord labels which are respectively translated from the FBAs, and the musical surface.

Additionally, we attached the text files ([example](https://github.com/juyaolongpaul/BCMCL/blob/master/Algorithm_D_all_chords.txt)), where each includes the chord labels for all the chorales. Slices left unlabelled by the algorithms (e.g., m. 8.1.5) are assigned label(s) from the previous slice (e.g., “Dm7” will be the chord label for m. 8.1.5).

![image](https://user-images.githubusercontent.com/9313094/89224905-47dad580-d5a7-11ea-86f9-474c6d66add8.png)

If you have any questions, please email to `yaolong.ju@mail.mcgill.ca`.

Shield: [![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a [Creative Commons Attribution 4.0 International
License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
