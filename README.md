# Eyetrain

Training a fast.ai model to recognzied the pupil-iris ratio

I have a dataset of ~150 images of eyes which contain the file name GoodPLR_[PLR]_[random number].
The dataset is small, so the model will not be very accurate. This is acceptable as it will later be taught using a larger dataset.

I am attempting to use a Convoluted Neural Network to predict the PLR based on the image.

What is the PLR?

The Pupil-Limbus Ratio is the diameter of the pupil divided by the diameter of the outer limit of the iris. Both are ellipses (approx) 
and the centres of both are the same coordinate.

The PLR is a robust measure of pupil dilation. Pupil dilation is a marker for states of arousal, and neurological injury.
