
# BERT Pre-Training and Inference Project

This repository contains Jupyter notebooks and associated files for the pre-training and inference phases of a BERT (Bidirectional Encoder Representations from Transformers) model. The project demonstrates the process of fine-tuning a pre-trained BERT model and visualizing its attention mechanisms to better understand how it processes textual data.

## Project Structure

- `pre-train-bert.ipynb`: This notebook handles the pre-training or fine-tuning of the BERT model using a specific dataset. It includes data loading, model configuration, training loop, and model saving.
- `bert-inference.ipynb`: This notebook demonstrates how to load the trained BERT model and perform inference. Key features include visualizations of the model's attention mechanisms to analyze how it interprets different textual inputs.

## Setup

To run the notebooks in this repository, you will need Python and several dependencies installed, including PyTorch and the Hugging Face `transformers` library. You can install the required packages using the following command:

```bash
pip install torch transformers matplotlib numpy
```

## Usage

1. **Pre-Training the BERT Model:**
   - Open the `pre-train-bert.ipynb` notebook.
   - Run the cells sequentially to train your model.
   - The trained model will be saved to a file named `bert_pretrained.pt`.

2. **Performing Inference:**
   - Ensure the trained model `bert_pretrained.pt` is in the same directory as your notebooks.
   - Open the `bert-inference.ipynb` notebook.
   - Run the cells to load the model and visualize its attention on different test sentences.

## Visualizing Attention

The inference notebook includes detailed visualizations of the attention layers within BERT. These visualizations help in understanding the focus areas of the model for different input tokens and can be a powerful tool in explaining model decisions.

## Contributing

Contributions to this project are welcome! You can contribute in several ways:

- Suggesting enhancements or new features.
- Reporting and fixing bugs.
- Improving documentation or comments.

Please feel free to fork the repository, make changes, and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


