Sentences were normalized to standard Kabyle orthography following the rules of the standardized Berber Latin alphabet. 

The text processing pipeline enforces the following strict rules:
* **Character Filtering:** Sentences containing characters outside the defined 34-letter Kabyle alphabet (such as French, Arabic, or English specific letters not adopted in standard *Taqbaylit*) are automatically rejected or manually corrected.
* **Length Constraints:** Duplicate sentences and text entries exceeding 15 words are removed to maintain optimal sequence lengths for end-to-end acoustic model training.
* **Punctuation Standards:** Preservation of word-compounding hyphens (e.g., *d-aserdun*) and standard punctuation, while stripping out anomalous formatting anomalies.
* **Human Validation:** Comprehensive manual validation by native speakers is systematically applied to all community-submitted text blocks before they transition into the active recording queue.
