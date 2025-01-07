# Ollama: Running LLM Locally and on Google Colab

Welcome to the Ollama repository! This repository provides step-by-step instructions for running Ollama locally and on Google Colab, enabling seamless interaction with large language models (LLMs).

## Overview
Ollama is a powerful tool to run and manage large language models with ease. You can install Ollama locally or use a cloud-based solution in Google Colab. This repository contains two main resources:

1. **Ollama.pdf**: General introduction and instructions on running Ollama locally.
2. **Run_Ollama_In_Colab**: Detailed instructions for setting up and running Ollama in Google Colab.

---

## Running Ollama Locally

To run Ollama locally, follow these steps:

1. **Install Ollama In Your System**  
   For Windows:
    ▪ Download the installer from the Ollama website:
    ▪ https://ollama.com/download/windows
   For Linux:
    ▪ Run the following command in your terminal:
    ```bash
    ▪ curl -fsSL https://ollama.com/install.sh | sh
    ```
    ▪ This command downloads and installs Ollama on your system.

1. **Run a Model**  
   Use the command:
   ```bash
   ollama run qwen:0.5b
   ```
   This runs the "qwen" model with a size of 0.5 billion parameters. Replace the model name and version to run other models.

2. **Remove a Model**  
   Free up space by removing a model:
   ```bash
   ollama rm qwen:0.5b
   ```

3. **Accessing More Resources**  
   Ollama also supports cloud-based usage in Google Colab. See below for instructions.

---

## Running Ollama in Google Colab

For those who prefer a cloud-based approach, you can set up and run Ollama in Google Colab with the steps provided in the Run_Ollama_In_Colab.ipynb file.

## Advantages of Using Google Colab
- No need for local installation.
- Accessible from any device with internet.

## Contact Us
If you have questions or want to connect, feel free to reach out:

- **Bilal Akhtar**  
  - GitHub: [BilalAkhtar88](https://github.com/BilalAkhtar88)  
  - LinkedIn: [Muhammad Bilal Akhtar](https://www.linkedin.com/in/muhammad-bilal-akhtar-a48265263/)

- **Ammar Aamir**  
  - GitHub: [AmmarAamir786](https://github.com/AmmarAamir786)  
  - LinkedIn: [Ammar Aamir](https://www.linkedin.com/in/ammar-aamir-0781722bb/)

---

## Contributing
We welcome contributions to improve this guide or add new features. Please create a pull request or contact us for collaboration opportunities.

## License
This project is open-source and licensed under the [MIT License](LICENSE).

```

Happy Learning! 🚀