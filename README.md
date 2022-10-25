This repo contains various Praat scripts, and R notebooks used in my own research and/or teaching.

# Research (Praat scripts)

## [Spectral analyses for fricatives and stops](https://jalalal-tamimi.github.io/Praat-Spectral-Analyses-fricatives-stops/)
This Praat script allows the user to obtain various spectral measures from fricatives and stops, similar to those reported in Al-Tamimi and Khattab (2015) on fricatives, and extends these to other measures and to stops. The script works for only on the sound files uploaded online, but can be modified by the user for any other fricatives/stops (changes required in lines 132 and 260). This script uses cepstral smoothing for fricatives instead of time-averaging as used in Al-Tamimi and Khattab (2015), following the literature that an appropriate spectral estimation (and with smoothing) provides the same linguistic information to e.g., multitaper spectra. 

## [Spectral tilt](https://jalalal-tamimi.github.io/Praat-Spectral-Tilt)

This Praat script allows to obtain the various acoustic metrics reported in Al-Tamimi (2017), including the normalised harmonic differences as used to estimate spectral tilt. The repo contains the actual script, two sound files and TextGrids, the results file and two folder containing spectra and images to be used as a first step for manual checking

## [Voice Quality measures](https://jalalal-tamimi.github.io/Praat-VQ-Measurements/)

This script provides various VQ measurements as averages for an interval (word level in the example). It provides mesurements for Jitter, Shimmer, Harmonics-to-Noise-Ratio (various ranges), CPP, Hammarberg Index, Energy components (various ranges), spectral slope and tilt, band energy differences and Glottal-to- Noise-Excitation (at 3500 and 4500 Hz). Most of these measures are adapted from the Acoustic Breahtiness Index.

## [Silence/Speech Detection](https://jalalal-tamimi.github.io/Praat-Silence-Detection/)

This script adapts the default settings in Praat to be user-dependent. It provides computations of f0 and intensity and adapts the silence threshold to the speaker's range.

## [Voicing detection](https://jalalal-tamimi.github.io/Praat-Voicing-detection/)

This script allows you detect voicing using the two-passe methods for f0 estimation and intensity.


## [F0 estimation](https://jalalal-tamimi.github.io/Praat-f0-Accurate-Estimation/)

This script allows you to estimate f0 accurately using the two-pass method, with and without smoothing.


## [Estimation of frame positions](https://jalalal-tamimi.github.io/Praat-Measurement-points/)

This script allows you to estimate the accurate positions of frames to obtain reliable results for formant, pitch and intensity results.


# Research (R notebooks)


## [GAMM Trombone 2019](https://jalalal-tamimi.github.io/GAMM-Trombone-2019/)

The link above contains the notebooks providing the full analysis of the article: **Heyne, M., Derrick, D., and Al-Tamimi, J. (2019). *"Native language influence on brass instrument performance: An application of generalized additive mixed models (GAMMs) to midsagittal ultrasound images of the tongue"*. Frontiers Research Topic: Models and Theories of Speech Production. Ed. Adamantios Gafos & Pascal van Lieshout. Volume 10, Article 2597, pp. 1-26. https://doi.org/10.3389/fpsyg.2019.02597**


## [Voicing and Gemination - VOT](https://jalalal-tamimi.github.io/R-Voicing-Gemination-VOT/)

The link above contains the notebooks providing the full analysis of the article: **Al-Tamimi, J. and Khattab, G., (2018). *Acoustic correlates of the voicing contrast in Lebanese Arabic singleton and geminate stops*. Invited manuscript for the special issue of Journal of Phonetics, "Marking 50 Years of Research on Voice Onset Time and the Voicing Contrast in the World’s Languages" (eds., T. Cho, G. Docherty & D. Whalen)." Vol: 71, pp. 306-325. https://doi.org/10.1016/j.wocn.2018.09.010**


## [Rating experiments](https://jalalal-tamimi.github.io/R-Rating-data/)

The link above contains the notebook providing the analysis of the rating experiment with Cumulative Logit Mixed-effects Modelling, presented in the article: **Khattab, G., Al-Tamimi, J., and Al-Siraih, W., (2018). "Nasalisation in the production of Iraqi Arabic pharyngeals". Phonetica, https://doi.org/10.1159/000487806**


## [GAMMs LabPhon 2018](https://jalalal-tamimi.github.io/R-GAMM-LabPhon18/)

The link above contains the notebook providing the analysis of of Ultrasound data using Generalised Additive Mixed-effects Modelling presented in a workshop I have presented at LabPhon 2018. 

# R training (R notebooks)

## [R-training full](https://jalalal-tamimi.github.io/R-Training/)

The link above presents the full material used during my teaching at undergraduate and master's degree at Université de Paris. The various notebooks build in difficulty, going from basics in R, to the Tidyverse, to visualisations, to statistics. A more advanced session is included (going from linear, to binary logistic regression, to cumulative logit regression for rating data, to linear mixed-effects modelling). We then move to PCA, Decision trees and Random Forests.

## [Introduction to R](https://jalalal-tamimi.github.io/R-Introduction-to-R/)

The link above presents the essential part of the workshop **Introduction to R**. This workshop was run as part of the "adventures in R meetup" and was supported by the R Consortium. The training was run in 2018.


## [Techniques in data analyses](https://jalalal-tamimi.github.io/R-Techniques-in-Data-Analyses/)

The link above provides links to various sessions I ran as part of the HASS faculty R training workshop at Newcastle University. This forms part of the "Adventures in R" group.  

## [Introduction to Random Forests](https://jalalal-tamimi.github.io/Intro-Random-Forests/)

The link above presents material used for the workshop: *introduction to Random Forest* delivered to the group: *[Sounds of Language and Speech: Aarhus University's phonetics and phonology (and more) research group](https://soundsoflanguageandspeech.wordpress.com/)*, on 16th June 2021 
