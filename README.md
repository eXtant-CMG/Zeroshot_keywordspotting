**Automated Keyword Spotting in Handwritten Documents Using CLIP-Model**

**Introduction:**

Digitization significantly influences the transmission, preservation, and analysis of handwritten documents. However, a gap exists between providing access to digital images and making their contents machine-readable and searchable. The current workflow heavily relies on Handwritten Text Recognition (HTR) through supervised machine learning.

**Challenges in Current Workflow:**

1. The quality of training data impacts the model's performance.
2. Introducing new handwriting requires time-consuming fine-tuning or training a new model.

**CLIP-Model as a Solution?**

This notebook aims to showcase how the Contrastive Language Image Pre-Training (CLIP) model can revolutionize this process. CLIP is a multimodal model with separate encoders for textual and visual information, trained to maximize cosine similarity for correct image-text pairs and minimize it for incorrect pairs. In the image below, CLIP's architecture to connect words to their handwritten word is visualised.

<img width="599" alt="Screenshot 2023-11-27 at 11 38 30" src="https://github.com/eXtant-CMG/Zeroshot/assets/72438295/459bbfc8-d277-4420-b979-90f1eb9f4c86">

**Versatility of CLIP:**

CLIP's broad training spectrum allows it to perform various tasks without requiring fine-tuning, an abiblity also refered to as zero-shot learning. Tasks include OCR, action recognition, and geo-localization.

**Exploring CLIP's Potential for Handwriting Recognition:**

The presentation tests CLIP's zero-shot capabilities on handwritten words using, among other datasets, the IAM dataset. The IAM dataset contains diverse handwriting samples from hundreds of writers, making it an ideal case study for assessing CLIP's performance in handling various handwriting styles.

**GitHub Demo:**

The accompanying GitHub page provides code demonstrating zero-shot keyword spotting using CLIP on multiple datasets. These experiments show CLIP's ability to efficiently browse digital images of handwritten documents without the need for manual transcriptions, addressing the challenges posed by the traditional HTR workflow.

**Conclusion:**

By leveraging CLIP's capabilities, the GitHub demo aims to facilitate the adoption of automated keyword spotting in handwritten documents, offering a more efficient and versatile solution for researchers and developers in the field of digitization.

<img width="1056" alt="Screenshot 2023-11-27 at 11 08 57" src="https://github.com/eXtant-CMG/Zeroshot/assets/72438295/aa6ff0bd-e1ae-4990-8482-43d70b174717">

