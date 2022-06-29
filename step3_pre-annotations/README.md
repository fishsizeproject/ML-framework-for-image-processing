# Step 3: Pre-annotations – accelerate manual annotation of images

This pipeline includes importing images from cloud storage, running an object detector using the module <i>inception_resnet_v2</i> a Keras image classification model pre-trained on Open Images Dataset V4 (Kuznetsova et al. 2020), converting the bounding boxes metadata to absolute coordinates and saving the metadata in VGG format (in a .csv file).

The pre-trained object detector was used to place bounding boxes around all fish shapes in the image, but the model can be used to detect 600 shapes, including elephant, lynx, bird, insect, shellfish, tree, plant and others (see “class names.csv”  <a href="https://storage.googleapis.com/openimages/web/download_v4.html"> here) </a>
)

