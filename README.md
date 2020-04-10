# RSR2015_trials

This repository includes the trials used in the paper [**Text Adaptation for Speaker Verification with Speaker-Text Factorized Embeddings**](https://ieeexplore.ieee.org/document/9054333). 

## Folder Structure

    .
    ├── trials
    │   ├── text_adapt                     # Test trials and enroll utterances where mismatch happens between enrollment and test data
    |   │   ├── eval_subset                # 10 subsets for testing (Table 6. in our paper)
    |   |   │   ├── 1
    |   |   |   │   ├── trials             # Test trials for subset 1
    |   |   |   │   ├── utt_adapt_text     # 10 random utterances from the development set to compute text embedding for adaptation (speakers are other from the evaluation set)
    |   |   │   ├── ..
    |   │   ├── enroll_spk2utt_td          # Text-dependent enrollment (check Section 4.1.2 in our paper)
    |   │   ├── enroll_spk2utt_tid         # Text-independent enrollment (check Section 4.1.2 in our paper)
    │   ├── text_dependent                 # Test trials and enroll utterances where mismatch happens between training and evaluation data
    |   │   ├── enroll_spk2utt             # Utterances for enrollment
    |   │   ├── trials_td                  # Text-dependent trials (Table 4. and Table 5. in our paper)
    |   │   ├── trials_tid                 # Text-independent trials (Table 3. in our paper)
    ├── LICENSE
    └── README.md

## Citation

    @INPROCEEDINGS{9054333,
        author={Y. {Yang} and S. {Wang} and X. {Gong} and Y. {Qian} and K. {Yu}},
        booktitle={ICASSP 2020 - 2020 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)},
        title={Text Adaptation for Speaker Verification with Speaker-Text Factorized Embeddings},
        year={2020},
        volume={},
        number={},
        pages={6454-6458},
    }
