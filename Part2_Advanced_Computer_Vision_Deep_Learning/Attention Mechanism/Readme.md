This is my implementation of Attention mechanisms code. The followings are the implementation steps I have used:

1. Implemented the scoring of all the annotations in one step using matrix multiplication.

2. Compute the dot product of the decoder hidden state transpose and the encoder hidden state. This gives me a score of each input and an idea of the vector that will get the most attention from the decoder.

3. Compute a softmax functin and apply it on the score.

4. Multiply each annotation by its score

5. Calculate the attention context vector.


Eh voila!

