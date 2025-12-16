Fully Self-contained:

No external files; text is hardcoded.

Can easily switch texts using the text variable.

2. Temperature Sampling for Creativity:

sample_with_temperature allows the model to pick characters probabilistically rather than always taking the highest probability.

Temperature controls creativity:

Lower (<1.0) → more predictable text

Higher (>1.0) → more random and creative text

3. Improved Text Generation:

Output is more natural and less repetitive.

Generates 50 characters after the start_seq sequence.

4. Other Features:

RNN with 50 hidden units (SimpleRNN)

One-hot encoding for input sequences and labels

100 epochs training (can be increased for better results)
