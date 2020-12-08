# Few-shot Voice Conversion with Reverberant Speech


## ABSTRACT
In this study, we propose FewsClon, a voice cloning system that can replicate a specific user’s timbre with only a small amount of speech data collected in a reverb environment. FewsClon is composed of 1) dereverb module and 2) cloning module. The dereverb module is a U-Net-based network that removes the reverb component included in the input signal, and is trained in a way that disentangles a given input’s source and its reverb components at the latent dimension.  The cloning module operates by transferring pre-trained multi-speaker TTS to small volume of speech data, and at this time, it is designed in a structure that independently model input pitch and text in order to learn timbre effectively from less data. In the experimental results, we showed that significant performance degradation occurs when signals collected in a reverb environment are used for voice cloning, and that this performance degradation is reduced when preprocessing with a network that effectively performs dereverberation tasks in various environments. In addition, we confirmed that the voice cloning module could successfully convey the speaker’s timbre with only 20 sentences (∼2 min) of training data through listening evaluation.


Project page with samples : https://dg22302.github.io/Few-shot-Voice-Cloning-in-Reverberant-Environment/
