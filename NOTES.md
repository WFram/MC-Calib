Please, rely on `configs/Insta360X4/calib_param_insta360X4_non_overlap.yml`.
You need to pass only one file, instead of a few ones, in order to get Hand-Eye (HE) calibration.
Also, see the code. Especially take care of:
* marker indices. Now some const valuesa are added according to their ID in the dict.
  Note, for the 1st board you should have indices 0-17, but for the second one: 17-36. Make sure you get these indices for the boards. The current setting is applied to the latest boarder configuration sent to Dmitriy
* which border to use. We have two. Check which border you use during CHARUCO extraction

