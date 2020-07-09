# Privacy Policy Classification with XLNet

This repository contains code for the ESORICS 2020 paper : Privacy Policy Classification with XLNet (short paper)

> <b>Abstract</b>. Popularization of privacy policies has become an attractive subject of research in recent years, notably after General Data Protection Regulation came into force in the European Union. While GDPR gives Data Subjects more rights and control over the use of their personal data, length and complexity of privacy policies can still prevent them from exercising those rights. An accepted way to improve the interpretability of privacy policies is through assigning understandable categories to every paragraph or segment in said documents. Current state of the art in privacy policy analysis has established a baseline in multi-label classification on the dataset containing 115 privacy policies, using BERT Transformers. In this paper, we propose a new classification model based on the XLNet. Trained on the same dataset, our model improves the baseline F1 macro and micro averages by 1-3\% for both majority vote and union-based gold standards. Moreover, the results reported by our XLNet-based model have been achieved without fine-tuning on domain-specific data, which reduces the training time and complexity, compared to the BERT-based model. To make our method reproducible, we report our hyper-parameters and provide access to all used resources, including code. This work may therefore be considered as a first step to establishing a new baseline for privacy policy classification.

This work is developed within the ASGARD project *Supported and funded by the Walloon region, Belgium.* , in particular, its RUNE track, whose objective is supporting the automation of privacy by design. One of the primary tasks of the track is translation of privacy policies, data processing agreements and other contracts into a machine-readable form.

### Getting started
1. Install NVIDIA Apex
2. Install Transformers library
3. Install Fast-BERT library
4. Run notebooks in /notebooks

## Citation

If you found our research helpful or influential please consider citing

    @inproceedings{Mustapha_et_al_2020,
        author = {Mustapha, M. and Krasnashchok, K. and Al Bassit, A. and Skhiri, S.},
        title = {Privacy Policy Classification with XLNet (short paper)},
        booktitle = {Proceedings of the European Conference on Research in Computer Security},
        year = {2020}
    }


## Libraries and data splits

Please refer to [Fast-BERT](https://github.com/kaushaltrivedi/fast-bert) and HuggingFace [pytorch-transformers](https://github.com/huggingface/pytorch-transformers) libraries for dependencies & installation steps , [Polisis_Benchmark](https://github.com/SmartDataAnalytics/Polisis_Benchmark) for data splits and original data.


## Contact
**Any question regarding this work can be addressed to rune@euranova.eu**

