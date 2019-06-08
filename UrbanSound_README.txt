UrbanSound
==========

Created By
----------

Justin Salamon*^, Christopher Jacoby* and Juan Pablo Bello*
* Music and Audio Research Lab (MARL), New York University, USA
^ Center for Urban Science and Progress (CUSP), New York University, USA
http://serv.cusp.nyu.edu/projects/urbansounddataset
http://marl.smusic.nyu.edu/
http://cusp.nyu.edu/

Version 1.0


Description
-----------

This dataset contains 1302 labeled sound recordings. Each recording is labeled with the start and end times of sound
events from 10 classes: air_conditioner, car_horn, children_playing, dog_bark, drilling, engine_idling, gun_shot,
jackhammer, siren, and street_music. Each recording may contain multiple sound events, but for each file only events 
from a single class are labeled. The classes are drawn from the urban sound taxonomy described in the following article,
which also includes a detailed description of the dataset and how it was compiled:

J. Salamon, C. Jacoby and J. P. Bello, "A Dataset and Taxonomy for Urban Sound Research", 
22nd ACM International Conference on Multimedia, Orlando USA, Nov. 2014.

All recordings were obtained from www.freesound.org. The files are pre-sorted into folders by the class of events 
that have been annotated for each file.

In addition to the sound recordings, each audio file is accompanied by two metadata files: a JSON file containing the
metadata provided by the Freesound API (description, tags, id, format, etc.); and a CSV file containing the sound event
annotations.


Audio Files Included
--------------------

1302 audio files of field recordings (see description above). The audio codec, sampling rate, bit depth, and 
number of channels are the same as those of the original file uploaded to Freesound (and hence may vary from file to 
file).


Meta-data Files Included
------------------------

Every audio file (e.g. 12345.wav) is accompanied by two metadata files (e.g. 12345.json and 12345.csv).

* JSON file: 
Contains the file metadata provided by the Freesound API in JSON format. Includes fields such as:
analysis_frames, analysis_stats, avg_rating, bitdepth, bitrate, channels, created, description, duration, filesize,
geotag, id, license, num_comments, num_downloads, num_ratings, original_filename, pack, preview-hq-mp3, preview-hq-ogg,
preview-lq-mp3, preview-lq-ogg, ref, samplerate, serve, similarity, spectral_l, spectral_m, tags, type, url, user, 
waveform_l, waveform_m.

* CSV file:
Contains the annotations of sound events. Each line represents an event, and contains four comma-separated values:
start time, end time, salience label and class label. The salience label is a (subjective) assessment of the sound's 
presence- 1 = foreground, 2 = background. The class label takes one of ten values: air_conditioner, car_horn, 
children_playing, dog_bark, drilling, engine_idling, gun_shot, jackhammer, siren, street_music. Note that for each file
only events from a single class (indicated by the name of the folder where the file resides) are annotated.


Please Acknowledge UrbanSound in Academic Research
----------------------------------------------------

When UrbanSound is used for academic research, we would highly appreciate it if scientific publications of works 
partly based on the UrbanSound dataset cite the following publication:

J. Salamon, C. Jacoby and J. P. Bello, "A Dataset and Taxonomy for Urban Sound Research", 
22nd ACM International Conference on Multimedia, Orlando USA, Nov. 2014.

The creation of this dataset was supported by a seed grant by NYU's Center for Urban Science and Progress (CUSP).


Conditions of Use
-----------------

Dataset compiled by Justin Salamon, Christopher Jacoby and Juan Pablo Bello. All files come from www.freesound.org. 
Please see FREESOUNDCREDITS.txt for an attribution list.
 
The UrbanSound dataset is offered free of charge for non-commercial use only under the terms of the Creative Commons 
Attribution Noncommercial License (by-nc), version 3.0: http://creativecommons.org/licenses/by-nc/3.0/
 
The dataset and its contents are made available on an "as is" basis and without warranties of any kind, including 
without limitation satisfactory quality and conformity, merchantability, fitness for a particular purpose, accuracy or 
completeness, or absence of errors. Subject to any liability that may not be excluded or limited by law, NYU is not 
liable for, and expressly excludes, all liability for loss or damage however and whenever caused to anyone by any use of
the UrbanSound dataset or any part of it.


Feedback
--------

Please help us improve UrbanSound by sending your feedback to: justin.salamon@nyu.edu or justin.salamon@gmail.com
In case of a problem report please include as many details as possible.
