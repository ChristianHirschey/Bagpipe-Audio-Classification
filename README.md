# Bagpipe Audio Classification
Multi-class audio classification deep learning model to classify bagpipe tunes into 3 distinct categories (Marches, Strathspeys, and Reels). Utilizes audio preprocessing techniques in TensorFlow, including resampling and normalizing volume. Uses Mel-frequency cepstral coefficients (MFCCs) for feature extraction to distinguish phrasing and tempo. The model is a CNN-based deep learning model trained on a unique dataset gathered using PyTube and Neil Clark Falkirk Piping's YouTube playlist containing 360 bagpipe recordings, achieving a classification accuracy of 76.67% in determining tune types. This accuracy is likely heavily limited due to the small size of pre-categorized bagpipe tunes available; in the future, I may find alternative sources for more data points to train a more accurate model.
