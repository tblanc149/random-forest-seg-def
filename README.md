# random-forest-seg-def

Spatially Adaptative Random Forest for automatic abdominal organ segmentation, last version. 

Developed a 3D supervoxel-based segmentation pipeline for abdominal T2 MRI (liver, right kidney, left kidney, spleen): TV-Bregman denoising, 3D SLIC supervoxel extraction, handcrafted intensity + spatial features per supervoxel, majority-vote labeling from ground truth masks, Random Forest training (with feature scaling), and 3D mask reconstruction from supervoxel predictions, evaluated with Dice scores and qualitative slice overlays. 

Completed as part of a group project.
