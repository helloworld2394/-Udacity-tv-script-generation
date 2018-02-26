# Udacity TV-Script-Generation Project
Udacity DLND TV script generation report file
**In version 1.2 of the Tensorflow, there was a problem in the script generation part, so I modified<br>
`pred_word = pick_word(probabilities[dyn_seq_length-1], int_to_vocab)` to<br>
`pred_word = pick_word(probabilities[0][dyn_seq_length-1], int_to_vocab)`.<br>**
There are no other modifications.
