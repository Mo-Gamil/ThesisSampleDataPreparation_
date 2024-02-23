# ThesisSampleDataPreparation_
Sample Data Preparation for training a swin transformer model for semantic segmentation and crop yield estimation
## Files description:
sen2Img folder: contains the 4 bands sentinel 2 image patches (120 patchs). images were downloaded in July, 2021
CDL_Patches folder: contains the cdl image patches (120 patches)
grid_geometries: contains the shapefile of the created grids. it is used to create the images patches of sentinel 2 and of the cdl layer
CDL_sample_IOWA folder: contains the cdl layer in 2021 of the chosen area of the shapefile 
dataset xls file: has the paths to sentinel 2 patches and the cdl patches an the corresponding crop yield values of corn and soybeans. It should be splitted into training, validation and testing sets.  
sentinelImgDownload: is used to download the sentinel 2 patches
Sample_data_prep_CDLPatches_And_Vis: used to create the cdl patches and visualise both sentinel 2 and cdl patches