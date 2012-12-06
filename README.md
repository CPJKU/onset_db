onset_db
========

This data set includes onset annotations which can be used for the evaluation of
onset detection algorithms. It does not include the audio files. If no download
link is given below, the data must be obtained by the original author.

`.onsets` contain the onset annotations, one per line, given in seconds.
The `original` branch includes the original annotations, the `master` branch the
modified onsets.

Data sources
------------
*  `sb_*` taken from the data set introduced by Sebastian Böck in:
   Universal Onset Detection with Bidirectional Long Short-Term Memory Neural
   Networks.
   F. Eyben, S. Böck, B. Schuller, and A. Graves.
   Proceedings of the 11th International Society for Music Information Retrieval
   Conference (ISMIR), 2010.
   It can be downloaded from: <http://mir.minimoog.org/sb-mir-db.zip>.
   The audio files are taken from the ISMIR 2004 ballroom data set located
   at: <http://mtg.upf.edu/ismir2004/contest/tempoContest/node5.html>.
   This set also includes the original and modified annotations for the `al_*`
   files.

*  `al_*` taken from the data set introduced by Alexandre Lacoste in:
   A supervised classification algorithm for note onset detection.
   A. Lacoste, and D. Eck.
   EURASIP Journal on Applied Signal Processing, 1, 2007.
   It can be downloaded from:
   <http://w3.ift.ulaval.ca/~allac88/dataset.tar.gz>.
   The audio files are taken from the ISMIR 2004 ballroom data set located
   at: <http://mtg.upf.edu/ismir2004/contest/tempoContest/node5.html>.

*  `ah_*` taken from the data set introduced by Andre Holzapfel in:
   Three dimensions of pitched instrument onset detection.
   A. Holzapfel, Y. Stylianou, A.C. Gedik, and B. Bozkurt.
   IEEE Transactions on Audio, Speech, and Language Processing, 18(6), 2010

*  `jg_*`taken from the data set introduced by John Glover in:
   Real-time Detection of Musical Onsets with Linear Prediction and Sinusoidal
   Modelling.
   J. Glover, V. Lazzarini, and J. Timoney.
   EURASIP Journal on Advances in Signal Processing, 68, 2011.
   The set can be dowloaded from:
   <https://github.com/downloads/johnglover/modal/onsets-1.0.tar.gz>

*  `jpb_*` taken from the data set introduced by Juan Pablo Bello in:
   A tutorial on onset detection in music signals.
   J. Bello, L. Daudet, S. Abdallah, C. Duxbury, M. Davies, and M. Sandler.
   IEEE Transactions on Speech and Audio Processing, 13(5), 2005

