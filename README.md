---

## license: cc-by-nc-sa-4.0

# A Data-driven Approach to the Longitudinal Study of Canine Vocal Pattern Development

**Paper:** https://dl.acm.org/doi/10.1145/3746027.3758175

**Dataset:** https://huggingface.co/datasets/ArlingtonCL2/Canine-Age-Transition-Vocalization-Dataset

**Citation:**

```bibtex
@inproceedings{lekhak2025data,
  title={A Data-driven Approach to the Longitudinal Study of Canine Vocal Pattern Development},
  author={Lekhak, Hridayesh and Dang, Tuan M. and Wang, Theron S. and Zhu, Kenny Q.},
  booktitle={Proceedings of the 33rd ACM International Conference on Multimedia},
  pages={12473--12482},
  year={2025},
  doi={10.1145/3746027.3758175}
}
```

## Canine Age Transition Vocalization Dataset

### Dataset Summary

The **Canine Age Transition Vocalization Dataset** is a large-scale longitudinal canine vocalization dataset designed to support research on how dog vocal patterns develop across the lifespan.

The dataset contains **79,142 Bark Units (BUs)** extracted from **55,718 Bark Sequences (Barkseqs)**, totaling **11.4 hours** of vocalizations from **125 individual dogs** across **6 breeds**. Each dog is associated with curated longitudinal metadata, including breed, age in months, developmental age group, and vocal development annotations.

Unlike most canine vocalization datasets, this resource enables longitudinal analysis of vocal development from puppyhood through adulthood by leveraging precisely verified age metadata collected over multiple years.

### Related Dataset

Researchers may also find our earlier DogSpeak dataset useful:

**DogSpeak Dataset:** https://huggingface.co/datasets/ArlingtonCL2/DogSpeak_Dataset

DogSpeak contains **77,202 Bark Sequences (Barkseqs)** from **156 individual dogs** across **5 breeds**: Chihuahua, German Shepherd, Husky, Pitbull, and Shiba Inu. DogSpeak also provides the biological sex of the dog, labeled as male or female, associated with each vocalization.

### Important Note Regarding Dataset Overlap

Some individual dogs may appear in both the DogSpeak dataset and the Canine Age Transition Vocalization Dataset.

If you use both datasets for training, evaluation, or benchmarking, we strongly recommend checking for overlapping dogs and avoiding train/test leakage. In many cases, it may be preferable to use only one of the datasets for a given experiment.

### Dataset Contents

The released dataset includes:

* Bark Unit audio files
* Parent Barkseq audio files
* Metadata for each Bark Unit
* Breed information
* Age in months
* Developmental age group labels
* Bark type annotations
* Elemental Dog Bark Unit (EDBU) transcripts
* Temporal alignment information between Bark Units and Barkseqs

Original usernames, source video identifiers, birthdates, and internal filesystem paths are not included in the public release.

### Citation

If you use this dataset in your research, please cite the paper above.

### License

This dataset is released under the **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)**.

You may share and adapt the dataset for non-commercial purposes, provided that appropriate credit is given and derivative works are distributed under the same license.
