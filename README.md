# RSR2015_trials

This repository includes the trials used in the paper **Text Adaptation for Speaker Verification with Speaker-Text Factorized Embeddings**. 

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

    @inproceedings{yang2020text,  
        title={Text Adaptation for Speaker Verification with Speaker-Text Factorized Embeddings},  
        author={Yexin, Yang and Shuai, Wang and Xun, Gong and Yanmin, Qian and Kai, Yu},  
        booktitle={2020 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP) },  
        pages={6454--6458},  
        year={2020}  
    }
