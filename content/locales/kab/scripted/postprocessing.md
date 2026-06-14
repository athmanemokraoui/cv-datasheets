We recommend the following post-processing steps when leveraging the Kabyle corpus for Automated Speech Recognition (ASR) and NLP training:

* **Audio Trimming:** Filter out audio clips tagged as `short-audio` (under 2 seconds) to minimize the presence of clipped or incomplete utterances.
* **Acoustic Modeling:** We strongly recommend evaluating character-level or phoneme-level modeling (such as Connectionist Temporal Classification - CTC), given the highly phonemic nature and precise grapheme-to-phoneme correspondence of standard Kabyle orthography.
* **Data Leakage Prevention:** Apply strict speaker-aware data splitting rules when partitioning data into train, development (dev), and test sets to guarantee that no individual speaker's voice appears across multiple splits.
