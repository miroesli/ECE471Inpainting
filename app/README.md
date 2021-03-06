# App Descriptions

## Execution of the Code

After downloading the required dataset (See [readme in images
folder](images/README.md)), merging the data and exporting the desired images to
the images folder, execute the data_loader to run the inpainting method on the
entire images folder.

```bash
python data_loader
```

## [images](images/)

Folder where the images to be inpainted from
[chalearn ECCV'18](http://chalearnlap.cvc.uab.es/dataset/30/description/) are
stored.

## [out](out/)

Folder where the images which have been inpainted are stored.

## [ece_inpaint](ece_inpaint.py)

Inpaints all images in images and then outputs the results to [out folder](out).

## [data_loader](data_loader.py)

Loads the data, then executes the [ece_inpaint](ece_inpaint.py) methods to
inpaint the image.

## [evaluator](evaluator.py)

Executes the analysis on image output.

## [evaluator](evaluator.py)

Evaluates the accuracy of our inpainting method

## [config](config.py)

Configuration settings for the inpainting method.
