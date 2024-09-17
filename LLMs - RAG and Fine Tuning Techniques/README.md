# Enhancing LLMs with RAG and Efficient Fine-Tuning Techniques

## Project Overview

This project enhances the accuracy and efficiency of Large Language Models (LLMs) by employing **Retrieval-Augmented Generation (RAG)** and advanced fine-tuning techniques like **Low-Rank Adaptation (LoRA)** and **Quantized LoRA (qLoRA)**. These methods significantly improve performance while reducing computational costs, making LLMs more scalable and effective in real-world applications.

### Key Features
- **Enhanced LLM Accuracy:** RAG dynamically integrates external data to boost model performance without the need for extensive retraining.
- **Efficient Fine-Tuning:** LoRA and qLoRA reduce computational costs while maintaining high performance.
- **Model Evaluation:** Techniques were tested on **Mistral (7B)**, **GEMA**, and **Llama2**, demonstrating substantial performance improvements.

### Technologies Used
- **Languages & Frameworks:**  
  - Python  
  - PyTorch  
  - Keras  
  - TensorFlow  

- **Libraries & Tools:**  
  - FAISS (Facebook AI Similarity Search)  
  - ChromaDB  

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    ```

2. Navigate to the project directory:
    ```bash
    cd your-repo-name
    ```

3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Fine-Tuning LLMs with LoRA/qLoRA:**
    - Run the `fine_tune.py` script to fine-tune your model with LoRA/qLoRA:
      ```bash
      python fine_tune.py --model Llama2 --method LoRA
      ```

2. **RAG Implementation:**
    - Use the `rag.py` script to apply Retrieval-Augmented Generation:
      ```bash
      python rag.py --model Llama2 --data data/chromaDB
      ```

3. **Evaluation:**
    - Run the `evaluate.py` script to evaluate model performance:
      ```bash
      python evaluate.py --model Llama2 --dataset mistral
      ```

## Results

- **Mistral (7B):** Significant improvement in response accuracy using RAG and fine-tuning techniques.
- **GEMA & Llama2:** Improved performance with reduced computational costs by employing qLoRA.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any questions or collaboration opportunities, feel free to reach out:
- **Email:** [rush2anshugupta@gmail.com](mailto:rush2anshugupta@gmail.com)
- **LinkedIn:** [Anshu Gupta](https://www.linkedin.com/in/anshu-gupta-471431190/)

