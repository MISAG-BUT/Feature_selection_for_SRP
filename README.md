# Feature_selection_for_SRP

Computed tomography (CT) imaging is a cornerstone in acute stroke diagnosis, with growing interest in leveraging radiomic features to better predict treatment outcomes. This study investigates feature selection techniques to identify key thrombus-related radiomic features from non-contrast CT (NCCT) and CT angiography (CTA) images for distinguishing patients with successful reperfusion from those without after endovascular treatment. This study identifies key image-derived features to differentiate patients with and without successful reperfusion (SRP and nSRP) after endovascular treatment. Using NCCT and CTA scans, our pipeline integrated feature preprocessing and feature selection methods followed by the evaluation of the selected features.

For the feature selection, run 'feature_selection_TICI_SRP.py' script. It is necessary to set paths to required images and clinical informations in the lines 308-316. If required, also the list of acquisitions may be changed in the line 320. 

For visualisation and evalusation of selected features, run 'evaluation.py' after setting path to results from the feature selection in the line 104.  

