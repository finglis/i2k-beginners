# QuPath for Beginners

## Requirements
-	QuPath (0.6.0-rc3 for the latest features). Installation instructions here.
-	Image(s). The following workshop uses [OS-2.ndpi, OS-3.ndpi](https://openslide.cs.cmu.edu/download/openslide-testdata/Hamamatsu/) and [BBBC007_v1_images](https://bbbc.broadinstitute.org/BBBC007). 

Optional Extensions via the extension manager within QuPath
-	[InstanSeg](https://github.com/qupath/qupath-extension-instanseg)
-	[OMERO](https://github.com/qupath/qupath-extension-omero)

## Orientation
### Welcome Window
The first window to pop up when running QuPath is the welcome window. It hopes to provide some useful QuPath links such as documentation or where to get help. From here you can also adjust the theme to either dark or light mode. settings to check for updates to the software and extensions (which we will discuss later) to make sure you have access to the latest features.

### QuPath Tour
A new feature for 0.6 is the QuPath Tour. Under the menu select Help → QuPath Tour to be guided around the applications interface and tools. We suggest opening an image first but this isn’t required and will be covering that in the next section.

## Basic Workflow

The following section takes you through a very basic workflow from image to results. We will use this workflow later to expand on certain aspects to tailor the workflow to different user needs. 

### Create a project
For easy organisation of images and analysis we recommend working on your images within [projects](https://qupath.readthedocs.io/en/0.5/docs/tutorials/projects.html). The quickest way to create a project is by making an empty folder on your desktop and dragging and dropping into the QuPath window. 

### Import images
Once you have a project, [images can also be added](https://qupath.readthedocs.io/en/0.5/docs/tutorials/projects.html#add-images) to the project by dragging and dropping them into QuPath. This will prompt the import window where you can finely tune some of the parameters if required. 

### Set the image stain type
When you open an imported image, you will be prompted to select the type of image. This lets QuPath know what stains the image has so it can assign them “channels”. For example, an H&E image would have a channel for Haematoxylin and Eosin after the default color profiles have been extracted. More on extracting the stains can be found in the [QuPath docs](https://qupath.readthedocs.io/en/0.5/docs/tutorials/separating_stains.html).

### Draw annotation
Define the region you would like to count some cells within using the [annotation tools](https://qupath.readthedocs.io/en/0.5/docs/starting/annotating.html) within the toolbar. If you create one you dislike, they can be easily deleted by selecting so they are yellow (instead of red) and then press the backspace key. The bigger the annotation the more effort it will take for the computer so it’s best to start with a smaller annotation for now and make it bigger once we know the parameters you’re looking for. 

### Detect cells
Now we have a region, we can count some cells! In the menu, select Analyze → Cell detection → Cell detection. Lots of parameters can be edited in this window to suit your specific cells and we reccomend spending some time finely tuning these to your cell types. 

### Investigate measurements

### Export measurements


