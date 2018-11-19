TensorBoard is a visualization software that comes with any standard TensorFlow installation.

writer = tf.summary.FileWriter([logdir], [graph])

where [logdir] is directory where event files are stored and graph is tensorflow program graph

How to run
$ tensorboard — logdir=”./graphs” — port 6006


More details at https://itnext.io/how-to-use-tensorboard-5d82f8654496

