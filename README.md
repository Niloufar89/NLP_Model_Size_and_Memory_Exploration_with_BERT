# NLP Model Size Exploration

This project explores the number of parameters in a BERT model and estimates the memory requirements for running inference on large models like GPT-3. 

## Key Challenges:
1. **Determining the number of parameters in a BERT model**: Understanding the model's complexity by counting its trainable parameters.
2. **Estimating memory requirements for inference**: Based on the number of parameters, calculate how much memory is needed to run the model on a machine.
3. **Understanding the implications for large models**: Applying this knowledge to even larger models like GPT-3 and estimating the infrastructure requirements.

### Python Script Overview:
- The script includes a function to compute the total number of parameters in a given model checkpoint.
- The BERT model is used to demonstrate how to determine parameter count and estimate memory usage for inference.

## How to Run the Code:
1. Install the necessary dependencies:
   ```bash
   pip install -r requirements.txt
