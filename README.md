# Few-shot Voice Conversion with Reverberant Speech


## ABSTRACT
In this study, we propose FewsClon, a voice cloning system that can generate random utterances by learning the user's timbre with only a small amount of speech data. FewsClon is composed of 1) dereverb module and 2) cloning module. The former is a module designed to obtain robust cloning quality in various room environments, and is trained in a way that penalizes the latent space for content and reverberation. The latter is designed as a module that separately  synthesizes pronunciation and pitch in order to reduce the complexity of the speech to be modeled. After training with a large amount of data, cloning module is trained by a few-shot transfer learning method. According to the experimental results, the reverb removal performance was higher than that of the baseline model, and it was confirmed that the performance was consistent in various environments. In addition, we confirmed that the MOS and similarity scores for cloned speech with a small amount of training data of about 20 sentences showed appropriate performance with 3.6 and 4.0 points, respectively.


Project page with samples : https://dg22302.github.io/Few-shot-Voice-Conversion-with-Reverberant-Speech/