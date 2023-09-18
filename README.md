# Zero-shot Prompting #
This project aims to choose the best prompt to use in Zero-shot text classification.
- Zero-shot text classification is a task where a pretrained model is used to classify examples from previously unseen classes.
- In this work, the semantic similarity between the prompt and the text is used to classify the text.
- Prompts are built using the semantics of the labels, without any prior knowledge of the tain/test data.
- A similarity score is computed between the text and each prompt. The text is assigned to the highest score.

<img width="784" alt="Screen Shot 2023-09-18 at 18 21 54" src="https://github.com/rayenebech/zero-shot-prompting/assets/34574318/38037903-4b44-45d5-a33f-f0ac8ffc3fca">
