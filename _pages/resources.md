---
title: "Auditory Intelligence Lab - Research Resources"
layout: textlay
excerpt: "Recommended Papers and Research Resources"
sitemap: false
permalink: /resources/
---

<style>
.resource-list {
    font-size: 16px;
    line-height: 1.8;
}

.resource-list h2 {
    font-size: 24px;
    font-weight: bold;
    margin-top: 50px;
    margin-bottom: 25px;
    padding-bottom: 12px;
    border-bottom: 1px solid #ddd;
}

.resource-list li {
    margin-bottom: 20px;
}

.resource-list a {
    color: #337ab7;
}
</style>

# Research Resources

## Recommended Papers

<div class="resource-list" markdown="1">

## I. Fundamental Concepts & Techniques

- **Perceptron:** [1] F. Rosenblatt, "The perceptron: A probabilistic model for information storage and organization in the brain," *Psychological Review*, vol. 65, no. 6, pp. 386–408, 1958.

- **Backpropagation & Feed Forward Neural Networks:** [2] D. E. Rumelhart, G. E. Hinton, and R. J. Williams, "Learning representations by back-propagating errors," *Nature*, vol. 323, no. 6088, pp. 533–536, Oct. 1986.

- **Optimization (Adam):** [3] D. P. Kingma and J. Ba, "Adam: A method for stochastic optimization," presented at the *3rd International Conference on Learning Representations (ICLR)*, San Diego, CA, USA, May 2015.

- **Regularization (Dropout):** [4] N. Srivastava, G. Hinton, A. Krizhevsky, I. Sutskever, and R. Salakhutdinov, "Dropout: A simple way to prevent neural networks from overfitting," *Journal of Machine Learning Research*, vol. 15, pp. 1929–1958, Jun. 2014.

- **Normalization (Batch Normalization):** [5] S. Ioffe and C. Szegedy, "Batch normalization: Accelerating deep network training by reducing internal covariate shift," in *Proceedings of the 32nd International Conference on Machine Learning (ICML)*, Lille, France, Jul. 2015, pp. 448–456.

- **Hidden Markov Models (HMM):** [6] L. R. Rabiner, "A tutorial on hidden Markov models and selected applications in speech recognition," *Proceedings of the IEEE*, vol. 77, no. 2, pp. 257–286, Feb. 1989.


## II. Sequence Modeling

- **Recurrent Neural Networks (RNN):** [7] J. L. Elman, "Finding structure in time," *Cognitive Science*, vol. 14, no. 2, pp. 179–211, Apr. 1990.

- **Long Short-Term Memory (LSTM):** [8] S. Hochreiter and J. Schmidhuber, "Long short-term memory," *Neural Computation*, vol. 9, no. 8, pp. 1735–1780, Nov. 1997.

- **Gated Recurrent Unit (GRU):** [9] K. Cho et al., "Learning phrase representations using RNN encoder-decoder for statistical machine translation," in *Proceedings of the 2014 Conference on Empirical Methods in Natural Language Processing (EMNLP)*, Doha, Qatar, Oct. 2014, pp. 1724–1734.


## III. Attention Mechanisms & Transformers

- **Sequence-to-Sequence (Seq2Seq):** [10] I. Sutskever, O. Vinyals, and Q. V. Le, "Sequence to sequence learning with neural networks," in *Advances in Neural Information Processing Systems 27 (NeurIPS 2014)*, Montreal, Canada, 2014, pp. 3104–3112.

- **Attention Mechanism (Bahdanau):** [11] D. Bahdanau, K. Cho, and Y. Bengio, "Neural machine translation by jointly learning to align and translate," presented at the *3rd International Conference on Learning Representations (ICLR)*, San Diego, CA, USA, May 2015.

- **Transformer:** [12] A. Vaswani et al., "Attention is all you need," in *Advances in Neural Information Processing Systems 30 (NeurIPS 2017)*, Long Beach, CA, USA, 2017, pp. 5998–6008.

- **Transformer-XL (Long-Range Dependencies):** [13] Z. Dai et al., "Transformer-XL: Attentive language models beyond a fixed-length context," in *Proceedings of the 57th Annual Meeting of the Association for Computational Linguistics (ACL)*, Florence, Italy, Jul. 2019, pp. 2978–2988.


## IV. Natural Language Processing & Representation

- **Word Embeddings (Word2Vec):** [14] T. Mikolov, K. Chen, G. Corrado, and J. Dean, "Efficient estimation of word representations in vector space," presented at the *Workshop Proceedings of the 1st International Conference on Learning Representations (ICLR)*, Scottsdale, AZ, USA, May 2013.

- **Word Embeddings (GloVe):** [15] J. Pennington, R. Socher, and C. D. Manning, "GloVe: Global vectors for word representation," in *Proceedings of the 2014 Conference on Empirical Methods in Natural Language Processing (EMNLP)*, Doha, Qatar, Oct. 2014, pp. 1532–1543.

- **Contextual Embeddings (BERT):** [16] J. Devlin, M.-W. Chang, K. Lee, and K. Toutanova, "BERT: Pre-training of deep bidirectional transformers for language understanding," in *Proceedings of the 2019 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies (NAACL-HLT)*, Minneapolis, MN, USA, Jun. 2019, pp. 4171–4186.


## V. Speech Recognition

- **Weighted Finite State Transducers (WFST):** [17] M. Mohri, F. Pereira, and M. Riley, "Weighted finite-state transducers in speech recognition," *Computer Speech & Language*, vol. 16, no. 1, pp. 69–88, Jan. 2002.

- **Deep Neural Networks for Acoustic Modeling (DNN-HMM):** [18] G. Hinton et al., "Deep neural networks for acoustic modeling in speech recognition: The shared views of four research groups," *IEEE Signal Processing Magazine*, vol. 29, no. 6, pp. 82–97, Nov. 2012.

- **Connectionist Temporal Classification (CTC):** [19] A. Graves, S. Fernández, F. Gomez, and J. Schmidhuber, "Connectionist temporal classification: Labelling unsegmented sequence data with recurrent neural networks," in *Proceedings of the 23rd International Conference on Machine Learning (ICML)*, Pittsburgh, PA, USA, Jun. 2006, pp. 369–376.

- **Sequence Transduction (RNN Transducer / RNN-T):** [20] A. Graves, "Sequence transduction with recurrent neural networks," presented at the *Workshop on Representation Learning, 30th International Conference on Machine Learning (ICML)*, Atlanta, GA, USA, Jun. 2012.

- **End-to-End ASR (Listen, Attend and Spell - LAS):** [21] W. Chan, N. Jaitly, Q. V. Le, and O. Vinyals, "Listen, attend and spell: A neural network for large vocabulary conversational speech recognition," in *Proceedings of the IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)*, Shanghai, China, Mar. 2016, pp. 4960–4964.

- **Self-Supervised Learning (Wav2Vec):** [22] S. Schneider, A. Baevski, J. Collobert, and M. Auli, "wav2vec: Unsupervised pre-training for speech recognition," in *Proceedings of Interspeech 2019*, Graz, Austria, Sep. 2019, pp. 3465–3469.

- **Self-Supervised Learning (Wav2Vec 2.0):** [23] A. Baevski, Y. Zhou, A. Mohamed, and M. Auli, "wav2vec 2.0: A framework for self-supervised learning of speech representations," in *Advances in Neural Information Processing Systems 33 (NeurIPS 2020)*, Virtual, 2020, pp. 12449–12460.

- **Conformer Architecture:** [24] A. Gulati et al., "Conformer: Convolution-augmented transformer for speech recognition," in *Proceedings of Interspeech 2020*, Shanghai, China (Virtual), Oct. 2020, pp. 5036–5040.

- **Self-Supervised Learning (HuBERT):** [25] W.-N. Hsu, B. Bolte, Y.-H. H. Tsai, K. Lakhotia, R. Salakhutdinov, and A. Mohamed, "HuBERT: Self-supervised speech representation learning by masked prediction of hidden units," *IEEE/ACM Transactions on Audio, Speech, and Language Processing*, vol. 29, pp. 3451–3460, Oct. 2021.


## VI. Convolutional Neural Networks

- **CNN (LeNet):** [26] Y. LeCun, L. Bottou, Y. Bengio, and P. Haffner, "Gradient-based learning applied to document recognition," *Proceedings of the IEEE*, vol. 86, no. 11, pp. 2278–2324, Nov. 1998.

- **CNN (AlexNet):** [27] A. Krizhevsky, I. Sutskever, and G. E. Hinton, "ImageNet classification with deep convolutional neural networks," in *Advances in Neural Information Processing Systems 25 (NeurIPS 2012)*, Lake Tahoe, NV, USA, 2012, pp. 1097–1105.

- **Residual Networks (ResNet):** [28] K. He, X. Zhang, S. Ren, and J. Sun, "Deep residual learning for image recognition," in *Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (CVPR)*, Las Vegas, NV, USA, Jun. 2016, pp. 770–778.


## VII. Generative Models

- **Generative Adversarial Networks (GAN):** [29] I. Goodfellow et al., "Generative adversarial nets," in *Advances in Neural Information Processing Systems 27 (NIPS 2014)*, Montreal, Canada, 2014, pp. 2672–2680.

- **Variational Autoencoders (VAE):** [30] D. P. Kingma and M. Welling, "Auto-encoding variational Bayes," presented at the *2nd International Conference on Learning Representations (ICLR)*, Banff, AB, Canada, Apr. 2014.

- **Normalizing Flows (RealNVP):** [31] L. Dinh, J. Sohl-Dickstein, and S. Bengio, "Density estimation using Real NVP," presented at the *5th International Conference on Learning Representations (ICLR)*, Toulon, France, Apr. 2017.

- **Denoising Diffusion Probabilistic Models (DDPM):** [32] J. Ho, A. Jain, and P. Abbeel, "Denoising diffusion probabilistic models," in *Advances in Neural Information Processing Systems 33 (NeurIPS 2020)*, Virtual, 2020, pp. 6840–6851.


## VIII. Speech Synthesis

- **WaveNet:** [33] A. van den Oord et al., "WaveNet: A generative model for raw audio," arXiv preprint arXiv:1609.03499, Sep. 2016.

- **Tacotron:** [34] Y. Wang et al., "Tacotron: Towards end-to-end speech synthesis," in *Proceedings of Interspeech 2017*, Stockholm, Sweden, Aug. 2017, pp. 4006–4010.

- **Tacotron 2:** [35] J. Shen et al., "Natural TTS synthesis by conditioning WaveNet on mel spectrogram predictions," in *Proceedings of the IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)*, Calgary, AB, Canada, Apr. 2018, pp. 4779–4783.

- **FastSpeech:** [36] Y. Ren et al., "FastSpeech: Fast, robust and controllable text to speech," in *Advances in Neural Information Processing Systems 32 (NeurIPS 2019)*, Vancouver, Canada, 2019, pp. 3165–3174.

- **MelGAN (Vocoder):** [37] K. Kumar et al., "MelGAN: Generative adversarial networks for conditional waveform synthesis," in *Advances in Neural Information Processing Systems 32 (NeurIPS 2019)*, Vancouver, Canada, 2019, pp. 14910–14921.

- **Glow-TTS:** [38] J. Kim, S. Kim, J. Kong, and S. Yoon, "Glow-TTS: A generative flow for text-to-speech via monotonic alignment search," in *Advances in Neural Information Processing Systems 33 (NeurIPS 2020)*, Virtual, 2020, pp. 10167–10178.

- **HiFi-GAN (Vocoder):** [39] J. Kong, J. Kim, and J. Bae, "HiFi-GAN: Generative adversarial networks for efficient and high fidelity speech synthesis," in *Advances in Neural Information Processing Systems 33 (NeurIPS 2020)*, Virtual, 2020, pp. 17022–17033.

- **Grad-TTS:** [40] V. Popov, I. Vovk, V. Gogoryan, T. Sadekova, and M. Kudinov, "Grad-TTS: A diffusion probabilistic model for text-to-speech," in *Proceedings of the 38th International Conference on Machine Learning (ICML)*, Virtual, Jul. 2021, pp. 8599–8609.

- **VITS:** [41] J. Kim, J. Kong, and J. Son, "Conditional variational autoencoder with adversarial learning for end-to-end text-to-speech," in *Proceedings of the 38th International Conference on Machine Learning (ICML)*, Virtual, Jul. 2021, pp. 5531–5541.

</div>
