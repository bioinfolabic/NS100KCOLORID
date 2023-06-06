# NS100KCOLORID

In the literature, the [Noscope](https://github.com/stanford-futuredata/noscope) dataset is one of the most popular datasets used to demonstrate query experiments about traffic surveillance.
It contains a surveillance video recorded for 60 hours and the respective labeled CSV dataset with annotations for each object (event) found in each frame. 
The CSV file contains 1,064,237 events (object detections) in 6,426,647 frames with the following fields: frame, objectname, confidence, xmin, ymin, xmax, ymax.
[Google Drive repository](https://drive.google.com/drive/folders/1znFWgDNH_rxof-ZTYHd_gwZR8iwY771t) of the original Noscope dataset files.

## A new database based on Noscope CSV labeled dataset

This new dataset called NS100KCOLORID was created from around 10\% of the original [Noscope](https://github.com/stanford-futuredata/noscope) dataset.

It was improved by including two more fields: the predominant color of the vehicle (red, blue, green, yellow, white, gray, black, pink, teal) and a unique Id of each object obtained using the DeepSort algorithm.

It contains 102,835 events in 858,806 frames. 

## Advantages

It offers more data to explore challenges. Several tests can be performed focused on CPU, memory consumption, and reactivity of different streaming video queries.

