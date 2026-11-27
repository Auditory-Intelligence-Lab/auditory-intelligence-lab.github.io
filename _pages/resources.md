---
title: "Auditory Intelligence Lab - Research Resources"
layout: textlay
excerpt: "Recommended Papers and Research Resources"
sitemap: false
permalink: /resources/
---

<div class="resources-header" markdown="0">

  <h1>Research Resources</h1>

  <p>Recommended Papers</p>

  <div class="resource-search-box" id="resource-search-box" hidden>

    <i data-lucide="search" aria-hidden="true"></i>

    <input type="search"
           id="resource-search"
           aria-label="Search papers"
           placeholder="Search papers or keywords..."
           autocomplete="off">

  </div>

</div>


<div class="resource-list" markdown="1">

## I. Fundamental Concepts & Techniques

- **Perceptron:**  
  [1] F. Rosenblatt, <span class="resource-paper-title">"The perceptron: A probabilistic model for information storage and organization in the brain,"</span> *Psychological Review*, vol. 65, no. 6, pp. 386–408, 1958.  
  [{{ site.data.resource_links["1"].label }}]({{ site.data.resource_links["1"].url }}){: .resource-paper-link target="_blank" rel="noopener noreferrer"}

- **Backpropagation & Feed Forward Neural Networks:**  
  [2] D. E. Rumelhart, G. E. Hinton, and R. J. Williams, <span class="resource-paper-title">"Learning representations by back-propagating errors,"</span> *Nature*, vol. 323, no. 6088, pp. 533–536, Oct. 1986.  
  [{{ site.data.resource_links["2"].label }}]({{ site.data.resource_links["2"].url }}){: .resource-paper-link target="_blank" rel="noopener noreferrer"}

- **Optimization (Adam):**  
  [3] D. P. Kingma and J. Ba, <span class="resource-paper-title">"Adam: A method for stochastic optimization,"</span> presented at the *3rd International Conference on Learning Representations (ICLR)*, San Diego, CA, USA, May 2015.  
  [{{ site.data.resource_links["3"].label }}]({{ site.data.resource_links["3"].url }}){: .resource-paper-link target="_blank" rel="noopener noreferrer"}

- **Regularization (Dropout):**  
  [4] N. Srivastava, G. Hinton, A. Krizhevsky, I. Sutskever, and R. Salakhutdinov, <span class="resource-paper-title">"Dropout: A simple way to prevent neural networks from overfitting,"</span> *Journal of Machine Learning Research*, vol. 15, pp. 1929–1958, Jun. 2014.  
  [{{ site.data.resource_links["4"].label }}]({{ site.data.resource_links["4"].url }}){: .resource-paper-link target="_blank" rel="noopener noreferrer"}

- **Normalization (Batch Normalization):**  
  [5] S. Ioffe and C. Szegedy, <span class="resource-paper-title">"Batch normalization: Accelerating deep network training by reducing internal covariate shift,"</span> in *Proceedings of the 32nd International Conference on Machine Learning (ICML)*, Lille, France, Jul. 2015, pp. 448–456.  
  [{{ site.data.resource_links["5"].label }}]({{ site.data.resource_links["5"].url }}){: .resource-paper-link target="_blank" rel="noopener noreferrer"}

- **Hidden Markov Models (HMM):**  
  [6] L. R. Rabiner, <span class="resource-paper-title">"A tutorial on hidden Markov models and selected applications in speech recognition,"</span> *Proceedings of the IEEE*, vol. 77, no. 2, pp. 257–286, Feb. 1989.  
  [{{ site.data.resource_links["6"].label }}]({{ site.data.resource_links["6"].url }}){: .resource-paper-link target="_blank" rel="noopener noreferrer"}


## II. Sequence Modeling

- **Recurrent Neural Networks (RNN):**  
  [7] J. L. Elman, <span class="resource-paper-title">"Finding structure in time,"</span> *Cognitive Science*, vol. 14, no. 2, pp. 179–211, Apr. 1990.  
  [{{ site.data.resource_links["7"].label }}]({{ site.data.resource_links["7"].url }}){: .resource-paper-link target="_blank" rel="noopener noreferrer"}

- **Long Short-Term Memory (LSTM):**  
  [8] S. Hochreiter and J. Schmidhuber, <span class="resource-paper-title">"Long short-term memory,"</span> *Neural Computation*, vol. 9, no. 8, pp. 1735–1780, Nov. 1997.  
  [{{ site.data.resource_links["8"].label }}]({{ site.data.resource_links["8"].url }}){: .resource-paper-link target="_blank" rel="noopener noreferrer"}

- **Gated Recurrent Unit (GRU):**  
  [9] K. Cho et al., <span class="resource-paper-title">"Learning phrase representations using RNN encoder-decoder for statistical machine translation,"</span> in *Proceedings of the 2014 Conference on Empirical Methods in Natural Language Processing (EMNLP)*, Doha, Qatar, Oct. 2014, pp. 1724–1734.  
  [{{ site.data.resource_links["9"].label }}]({{ site.data.resource_links["9"].url }}){: .resource-paper-link target="_blank" rel="noopener noreferrer"}


## III. Attention Mechanisms & Transformers

- **Sequence-to-Sequence (Seq2Seq):**  
  [10] I. Sutskever, O. Vinyals, and Q. V. Le, <span class="resource-paper-title">"Sequence to sequence learning with neural networks,"</span> in *Advances in Neural Information Processing Systems 27 (NeurIPS 2014)*, Montreal, Canada, 2014, pp. 3104–3112.  
  [{{ site.data.resource_links["10"].label }}]({{ site.data.resource_links["10"].url }}){: .resource-paper-link target="_blank" rel="noopener noreferrer"}

- **Attention Mechanism (Bahdanau):**  
  [11] D. Bahdanau, K. Cho, and Y. Bengio, <span class="resource-paper-title">"Neural machine translation by jointly learning to align and translate,"</span> presented at the *3rd International Conference on Learning Representations (ICLR)*, San Diego, CA, USA, May 2015.  
  [{{ site.data.resource_links["11"].label }}]({{ site.data.resource_links["11"].url }}){: .resource-paper-link target="_blank" rel="noopener noreferrer"}

- **Transformer:**  
  [12] A. Vaswani et al., <span class="resource-paper-title">"Attention is all you need,"</span> in *Advances in Neural Information Processing Systems 30 (NeurIPS 2017)*, Long Beach, CA, USA, 2017, pp. 5998–6008.  
  [{{ site.data.resource_links["12"].label }}]({{ site.data.resource_links["12"].url }}){: .resource-paper-link target="_blank" rel="noopener noreferrer"}

- **Transformer-XL (Long-Range Dependencies):**  
  [13] Z. Dai et al., <span class="resource-paper-title">"Transformer-XL: Attentive language models beyond a fixed-length context,"</span> in *Proceedings of the 57th Annual Meeting of the Association for Computational Linguistics (ACL)*, Florence, Italy, Jul. 2019, pp. 2978–2988.  
  [{{ site.data.resource_links["13"].label }}]({{ site.data.resource_links["13"].url }}){: .resource-paper-link target="_blank" rel="noopener noreferrer"}


## IV. Natural Language Processing & Representation

- **Word Embeddings (Word2Vec):**  
  [14] T. Mikolov, K. Chen, G. Corrado, and J. Dean, <span class="resource-paper-title">"Efficient estimation of word representations in vector space,"</span> presented at the *Workshop Proceedings of the 1st International Conference on Learning Representations (ICLR)*, Scottsdale, AZ, USA, May 2013.  
  [{{ site.data.resource_links["14"].label }}]({{ site.data.resource_links["14"].url }}){: .resource-paper-link target="_blank" rel="noopener noreferrer"}

- **Word Embeddings (GloVe):**  
  [15] J. Pennington, R. Socher, and C. D. Manning, <span class="resource-paper-title">"GloVe: Global vectors for word representation,"</span> in *Proceedings of the 2014 Conference on Empirical Methods in Natural Language Processing (EMNLP)*, Doha, Qatar, Oct. 2014, pp. 1532–1543.  
  [{{ site.data.resource_links["15"].label }}]({{ site.data.resource_links["15"].url }}){: .resource-paper-link target="_blank" rel="noopener noreferrer"}

- **Contextual Embeddings (BERT):**  
  [16] J. Devlin, M.-W. Chang, K. Lee, and K. Toutanova, <span class="resource-paper-title">"BERT: Pre-training of deep bidirectional transformers for language understanding,"</span> in *Proceedings of the 2019 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies (NAACL-HLT)*, Minneapolis, MN, USA, Jun. 2019, pp. 4171–4186.  
  [{{ site.data.resource_links["16"].label }}]({{ site.data.resource_links["16"].url }}){: .resource-paper-link target="_blank" rel="noopener noreferrer"}


## V. Speech Recognition

- **Weighted Finite State Transducers (WFST):**  
  [17] M. Mohri, F. Pereira, and M. Riley, <span class="resource-paper-title">"Weighted finite-state transducers in speech recognition,"</span> *Computer Speech & Language*, vol. 16, no. 1, pp. 69–88, Jan. 2002.  
  [{{ site.data.resource_links["17"].label }}]({{ site.data.resource_links["17"].url }}){: .resource-paper-link target="_blank" rel="noopener noreferrer"}

- **Deep Neural Networks for Acoustic Modeling (DNN-HMM):**  
  [18] G. Hinton et al., <span class="resource-paper-title">"Deep neural networks for acoustic modeling in speech recognition: The shared views of four research groups,"</span> *IEEE Signal Processing Magazine*, vol. 29, no. 6, pp. 82–97, Nov. 2012.  
  [{{ site.data.resource_links["18"].label }}]({{ site.data.resource_links["18"].url }}){: .resource-paper-link target="_blank" rel="noopener noreferrer"}

- **Connectionist Temporal Classification (CTC):**  
  [19] A. Graves, S. Fernández, F. Gomez, and J. Schmidhuber, <span class="resource-paper-title">"Connectionist temporal classification: Labelling unsegmented sequence data with recurrent neural networks,"</span> in *Proceedings of the 23rd International Conference on Machine Learning (ICML)*, Pittsburgh, PA, USA, Jun. 2006, pp. 369–376.  
  [{{ site.data.resource_links["19"].label }}]({{ site.data.resource_links["19"].url }}){: .resource-paper-link target="_blank" rel="noopener noreferrer"}

- **Sequence Transduction (RNN Transducer / RNN-T):**  
  [20] A. Graves, <span class="resource-paper-title">"Sequence transduction with recurrent neural networks,"</span> presented at the *Workshop on Representation Learning, 30th International Conference on Machine Learning (ICML)*, Atlanta, GA, USA, Jun. 2012.  
  [{{ site.data.resource_links["20"].label }}]({{ site.data.resource_links["20"].url }}){: .resource-paper-link target="_blank" rel="noopener noreferrer"}

- **End-to-End ASR (Listen, Attend and Spell - LAS):**  
  [21] W. Chan, N. Jaitly, Q. V. Le, and O. Vinyals, <span class="resource-paper-title">"Listen, attend and spell: A neural network for large vocabulary conversational speech recognition,"</span> in *Proceedings of the IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)*, Shanghai, China, Mar. 2016, pp. 4960–4964.  
  [{{ site.data.resource_links["21"].label }}]({{ site.data.resource_links["21"].url }}){: .resource-paper-link target="_blank" rel="noopener noreferrer"}

- **Self-Supervised Learning (Wav2Vec):**  
  [22] S. Schneider, A. Baevski, J. Collobert, and M. Auli, <span class="resource-paper-title">"wav2vec: Unsupervised pre-training for speech recognition,"</span> in *Proceedings of Interspeech 2019*, Graz, Austria, Sep. 2019, pp. 3465–3469.  
  [{{ site.data.resource_links["22"].label }}]({{ site.data.resource_links["22"].url }}){: .resource-paper-link target="_blank" rel="noopener noreferrer"}

- **Self-Supervised Learning (Wav2Vec 2.0):**  
  [23] A. Baevski, Y. Zhou, A. Mohamed, and M. Auli, <span class="resource-paper-title">"wav2vec 2.0: A framework for self-supervised learning of speech representations,"</span> in *Advances in Neural Information Processing Systems 33 (NeurIPS 2020)*, Virtual, 2020, pp. 12449–12460.  
  [{{ site.data.resource_links["23"].label }}]({{ site.data.resource_links["23"].url }}){: .resource-paper-link target="_blank" rel="noopener noreferrer"}

- **Conformer Architecture:**  
  [24] A. Gulati et al., <span class="resource-paper-title">"Conformer: Convolution-augmented transformer for speech recognition,"</span> in *Proceedings of Interspeech 2020*, Shanghai, China (Virtual), Oct. 2020, pp. 5036–5040.  
  [{{ site.data.resource_links["24"].label }}]({{ site.data.resource_links["24"].url }}){: .resource-paper-link target="_blank" rel="noopener noreferrer"}

- **Self-Supervised Learning (HuBERT):**  
  [25] W.-N. Hsu, B. Bolte, Y.-H. H. Tsai, K. Lakhotia, R. Salakhutdinov, and A. Mohamed, <span class="resource-paper-title">"HuBERT: Self-supervised speech representation learning by masked prediction of hidden units,"</span> *IEEE/ACM Transactions on Audio, Speech, and Language Processing*, vol. 29, pp. 3451–3460, Oct. 2021.  
  [{{ site.data.resource_links["25"].label }}]({{ site.data.resource_links["25"].url }}){: .resource-paper-link target="_blank" rel="noopener noreferrer"}


## VI. Convolutional Neural Networks

- **CNN (LeNet):**  
  [26] Y. LeCun, L. Bottou, Y. Bengio, and P. Haffner, <span class="resource-paper-title">"Gradient-based learning applied to document recognition,"</span> *Proceedings of the IEEE*, vol. 86, no. 11, pp. 2278–2324, Nov. 1998.  
  [{{ site.data.resource_links["26"].label }}]({{ site.data.resource_links["26"].url }}){: .resource-paper-link target="_blank" rel="noopener noreferrer"}

- **CNN (AlexNet):**  
  [27] A. Krizhevsky, I. Sutskever, and G. E. Hinton, <span class="resource-paper-title">"ImageNet classification with deep convolutional neural networks,"</span> in *Advances in Neural Information Processing Systems 25 (NeurIPS 2012)*, Lake Tahoe, NV, USA, 2012, pp. 1097–1105.  
  [{{ site.data.resource_links["27"].label }}]({{ site.data.resource_links["27"].url }}){: .resource-paper-link target="_blank" rel="noopener noreferrer"}

- **Residual Networks (ResNet):**  
  [28] K. He, X. Zhang, S. Ren, and J. Sun, <span class="resource-paper-title">"Deep residual learning for image recognition,"</span> in *Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (CVPR)*, Las Vegas, NV, USA, Jun. 2016, pp. 770–778.  
  [{{ site.data.resource_links["28"].label }}]({{ site.data.resource_links["28"].url }}){: .resource-paper-link target="_blank" rel="noopener noreferrer"}


## VII. Generative Models

- **Generative Adversarial Networks (GAN):**  
  [29] I. Goodfellow et al., <span class="resource-paper-title">"Generative adversarial nets,"</span> in *Advances in Neural Information Processing Systems 27 (NIPS 2014)*, Montreal, Canada, 2014, pp. 2672–2680.  
  [{{ site.data.resource_links["29"].label }}]({{ site.data.resource_links["29"].url }}){: .resource-paper-link target="_blank" rel="noopener noreferrer"}

- **Variational Autoencoders (VAE):**  
  [30] D. P. Kingma and M. Welling, <span class="resource-paper-title">"Auto-encoding variational Bayes,"</span> presented at the *2nd International Conference on Learning Representations (ICLR)*, Banff, AB, Canada, Apr. 2014.  
  [{{ site.data.resource_links["30"].label }}]({{ site.data.resource_links["30"].url }}){: .resource-paper-link target="_blank" rel="noopener noreferrer"}

- **Normalizing Flows (RealNVP):**  
  [31] L. Dinh, J. Sohl-Dickstein, and S. Bengio, <span class="resource-paper-title">"Density estimation using Real NVP,"</span> presented at the *5th International Conference on Learning Representations (ICLR)*, Toulon, France, Apr. 2017.  
  [{{ site.data.resource_links["31"].label }}]({{ site.data.resource_links["31"].url }}){: .resource-paper-link target="_blank" rel="noopener noreferrer"}

- **Denoising Diffusion Probabilistic Models (DDPM):**  
  [32] J. Ho, A. Jain, and P. Abbeel, <span class="resource-paper-title">"Denoising diffusion probabilistic models,"</span> in *Advances in Neural Information Processing Systems 33 (NeurIPS 2020)*, Virtual, 2020, pp. 6840–6851.  
  [{{ site.data.resource_links["32"].label }}]({{ site.data.resource_links["32"].url }}){: .resource-paper-link target="_blank" rel="noopener noreferrer"}


## VIII. Speech Synthesis

- **WaveNet:**  
  [33] A. van den Oord et al., <span class="resource-paper-title">"WaveNet: A generative model for raw audio,"</span> arXiv preprint arXiv:1609.03499, Sep. 2016.  
  [{{ site.data.resource_links["33"].label }}]({{ site.data.resource_links["33"].url }}){: .resource-paper-link target="_blank" rel="noopener noreferrer"}

- **Tacotron:**  
  [34] Y. Wang et al., <span class="resource-paper-title">"Tacotron: Towards end-to-end speech synthesis,"</span> in *Proceedings of Interspeech 2017*, Stockholm, Sweden, Aug. 2017, pp. 4006–4010.  
  [{{ site.data.resource_links["34"].label }}]({{ site.data.resource_links["34"].url }}){: .resource-paper-link target="_blank" rel="noopener noreferrer"}

- **Tacotron 2:**  
  [35] J. Shen et al., <span class="resource-paper-title">"Natural TTS synthesis by conditioning WaveNet on mel spectrogram predictions,"</span> in *Proceedings of the IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)*, Calgary, AB, Canada, Apr. 2018, pp. 4779–4783.  
  [{{ site.data.resource_links["35"].label }}]({{ site.data.resource_links["35"].url }}){: .resource-paper-link target="_blank" rel="noopener noreferrer"}

- **FastSpeech:**  
  [36] Y. Ren et al., <span class="resource-paper-title">"FastSpeech: Fast, robust and controllable text to speech,"</span> in *Advances in Neural Information Processing Systems 32 (NeurIPS 2019)*, Vancouver, Canada, 2019, pp. 3165–3174.  
  [{{ site.data.resource_links["36"].label }}]({{ site.data.resource_links["36"].url }}){: .resource-paper-link target="_blank" rel="noopener noreferrer"}

- **MelGAN (Vocoder):**  
  [37] K. Kumar et al., <span class="resource-paper-title">"MelGAN: Generative adversarial networks for conditional waveform synthesis,"</span> in *Advances in Neural Information Processing Systems 32 (NeurIPS 2019)*, Vancouver, Canada, 2019, pp. 14910–14921.  
  [{{ site.data.resource_links["37"].label }}]({{ site.data.resource_links["37"].url }}){: .resource-paper-link target="_blank" rel="noopener noreferrer"}

- **Glow-TTS:**  
  [38] J. Kim, S. Kim, J. Kong, and S. Yoon, <span class="resource-paper-title">"Glow-TTS: A generative flow for text-to-speech via monotonic alignment search,"</span> in *Advances in Neural Information Processing Systems 33 (NeurIPS 2020)*, Virtual, 2020, pp. 10167–10178.  
  [{{ site.data.resource_links["38"].label }}]({{ site.data.resource_links["38"].url }}){: .resource-paper-link target="_blank" rel="noopener noreferrer"}

- **HiFi-GAN (Vocoder):**  
  [39] J. Kong, J. Kim, and J. Bae, <span class="resource-paper-title">"HiFi-GAN: Generative adversarial networks for efficient and high fidelity speech synthesis,"</span> in *Advances in Neural Information Processing Systems 33 (NeurIPS 2020)*, Virtual, 2020, pp. 17022–17033.  
  [{{ site.data.resource_links["39"].label }}]({{ site.data.resource_links["39"].url }}){: .resource-paper-link target="_blank" rel="noopener noreferrer"}

- **Grad-TTS:**  
  [40] V. Popov, I. Vovk, V. Gogoryan, T. Sadekova, and M. Kudinov, <span class="resource-paper-title">"Grad-TTS: A diffusion probabilistic model for text-to-speech,"</span> in *Proceedings of the 38th International Conference on Machine Learning (ICML)*, Virtual, Jul. 2021, pp. 8599–8609.  
  [{{ site.data.resource_links["40"].label }}]({{ site.data.resource_links["40"].url }}){: .resource-paper-link target="_blank" rel="noopener noreferrer"}

- **VITS:**  
  [41] J. Kim, J. Kong, and J. Son, <span class="resource-paper-title">"Conditional variational autoencoder with adversarial learning for end-to-end text-to-speech,"</span> in *Proceedings of the 38th International Conference on Machine Learning (ICML)*, Virtual, Jul. 2021, pp. 5531–5541.  
  [{{ site.data.resource_links["41"].label }}]({{ site.data.resource_links["41"].url }}){: .resource-paper-link target="_blank" rel="noopener noreferrer"}

</div>

<script>
(function () {

    const list = document.querySelector('.resource-list');
    const search = document.getElementById('resource-search');
    const searchBox = document.getElementById('resource-search-box');

    if (!list || !search || !searchBox) return;


    /* 1. Collect Research Topics */

    const groups = [];
    let current = null;

    Array.from(list.children).forEach(function (element) {

        if (element.tagName === 'H2') {

            current = {
                heading: element,
                title: element.textContent.trim(),
                lists: [],
                papers: []
            };

            if (!element.id) {
                element.id = 'resource-topic-' + (groups.length + 1);
            }

            groups.push(current);

        } else if (element.tagName === 'UL' && current) {

            current.lists.push(element);

            Array.from(element.children).forEach(function (item) {

                if (item.tagName === 'LI') {
                    current.papers.push(item);
                }

            });

        }

    });

    if (!groups.length) return;


    /* 2. Create Sidebar */

    const layout = document.createElement('div');
    layout.className = 'resources-layout';

    const sidebar = document.createElement('aside');
    sidebar.className = 'resources-sidebar';

    const nav = document.createElement('nav');
    nav.setAttribute('aria-label', 'Research topics');

    const label = document.createElement('h4');
    label.textContent = 'Topics';

    nav.appendChild(label);

    groups.forEach(function (group) {

        const link = document.createElement('a');

        link.href = '#' + group.heading.id;
        link.textContent = group.title.replace(/^[IVX]+\.\s*/, '');

        nav.appendChild(link);

        group.link = link;

    });

    sidebar.appendChild(nav);

    list.parentNode.insertBefore(layout, list);

    layout.appendChild(sidebar);
    layout.appendChild(list);


    /* 3. Empty Search Results */

    const empty = document.createElement('p');

    empty.className = 'resource-empty';
    empty.textContent = 'No papers found.';
    empty.setAttribute('role', 'status');
    empty.hidden = true;

    list.appendChild(empty);


    /* 4. Active Topic */

    function updateActiveTopic() {

        const visible = groups.filter(function (group) {
            return !group.heading.hidden;
        });

        let active = visible[0];

        visible.forEach(function (group) {

            if (group.heading.getBoundingClientRect().top <= 150) {
                active = group;
            }

        });

        groups.forEach(function (group) {

            const selected = group === active;

            group.link.classList.toggle('active', selected);

            if (selected) {
                group.link.setAttribute('aria-current', 'location');
            } else {
                group.link.removeAttribute('aria-current');
            }

        });

    }


    /* 5. Paper Search */

    function normalize(value) {

        return value
            .normalize('NFKC')
            .toLowerCase()
            .trim();

    }

    function filterPapers() {

        const keywords = normalize(search.value)
            .split(/\s+/)
            .filter(Boolean);

        let totalVisible = 0;

        groups.forEach(function (group) {

            let visible = 0;

            group.papers.forEach(function (paper) {

                const content = normalize(
                    group.title + ' ' + paper.textContent
                );

                const matches = keywords.every(function (word) {
                    return content.includes(word);
                });

                paper.hidden = !matches;

                if (matches) {
                    visible++;
                    totalVisible++;
                }

            });

            group.heading.hidden = visible === 0;
            group.link.hidden = visible === 0;

            group.lists.forEach(function (ul) {

                ul.hidden = !Array.from(ul.children).some(function (li) {
                    return li.tagName === 'LI' && !li.hidden;
                });

            });

        });

        empty.hidden = totalVisible !== 0;

        updateActiveTopic();

    }


    /* 6. Initialize */

    searchBox.hidden = false;

    search.addEventListener('input', filterPapers);

    window.addEventListener('scroll', updateActiveTopic, {
        passive: true
    });

    window.addEventListener('resize', updateActiveTopic);
    window.addEventListener('load', updateActiveTopic);

    filterPapers();

})();
</script>