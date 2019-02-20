# BEP001 examples

This branch of the BEP001 repository contains some practical examples of what a BIDS-compatible qMRI dataset will look like. 

You can find more about the BEP001 addition to the BIDS standard, and the rationale for the additions/changes that it brings to the BIDS format, here: https://github.com/bids-standard/bep001.

 *The datasets in this branch contain empty data files, which might be useful for building simple software tests. 
 The current branch may eventually be merged with the bids-examples branch of the main bids-standard repo: https://github.com/bids-standard/bids-examples, in which case this disclaimer will be redundant.*


## Example 1 (ds-01): multi-echo FLASH dataset
This is a sample dataset from a single FLASH sequence, which yields multiple images, corresponding to different echo times. This data have been used to calculate a quantitative susceptibility map, as well as a T2* map, which are both part of the example dataset.

## Example 2 (ds-02): MP2RAGE
This is a sample dataset from a standard MP2RAGE sequence, which includes two GRE images acquired after a single inversion pulse. This data have been used to create a T1-map, as well as a T1-weighted image, corrected for B0 and B1-inhomogeneities, which are both part of the example dataset.

## Example 3 (ds-03): multi-echo MP2RAGE dataset
This is a sample dataset from an MP2RAGE sequence with two inversion times, and, for the second inversion time, 4 different echoes.

## Example 4 (ds-04): MultiParameter Mapping (MPM) dataset
This is a sample dataset from a MultiParameter Mapping (MPM) sequence (as per Weiskopf et al., 2013), which yields multi-echo FLASH scans that are predominantly T1-, PD-, or MT-weighted by changing repetition time and flip angle.

*example 4 might still be a work in progress, check the BEP001 google doc https://docs.google.com/document/d/1QwfHyBzOyFWOLO4u_kkojLpUhW0-4_M7Ubafu9Gf4Gg/edit# for notes on it*
