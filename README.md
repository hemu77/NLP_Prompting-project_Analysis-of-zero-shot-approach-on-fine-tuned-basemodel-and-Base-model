# NLP_Prompting-project_Analysis-of-zero-shot-approach-on-fine-tuned-basemodel-and-untrained-Base-model
This project involves fine-tuning the Mistral-7B model for generating responses to medical queries using a medical dataset. The aim is to analyse whether the fine tuning helps in better evaluation of the model or not.
## Dataset

The dataset used for tis project is: [AI Medical Chatbot Dataset](https://huggingface.co/datasets/ruslanmv/ai-medical-chatbot), which contains domain-specific queries of doctor and patients

## How to Run the Code
you have to run this in Google colab in T4 GPU in order to completely run my code.
1. **Clone the repository**:
   ```bash
   git clone <[repository-url](https://github.com/hemu77/NLP_Prompting-project_Analysis-of-zero-shot-approach-on-fine-tuned-basemodel-and-Base-model.git)>
2. Follow the commands in fine_tuned_model_evaluation_final.ipynb file ;followed by the base_model_evaluation.ipynb

## Results

The following table consisting of the average metric scores obtained from the fine-tuned Mistral-7B model compared to the base model:

| Metric         | Fine-Tuned Model | Base Model |
|----------------|------------------|------------|
| BERT Precision  | 0.8223           | 0.8195     |
| BERT Recall     | 0.8217           | 0.8252     |
| BERT F1        | 0.8219           | 0.8222     |
| ROUGE-1       | 0.2296           | 0.2213     |
| ROUGE-2       | 0.0323           | 0.0273     |
| ROUGE-L       | 0.1203           | 0.1140     |
| ROUGE-Lsum    | 0.1203           | 0.1283     |


   
