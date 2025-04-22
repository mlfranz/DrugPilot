# DrugPilot: A Comprehensive LLM Agent Framework for Drug Discovery

**DrugPilot** is an advanced LLM-based agent framework specifically designed for drug discovery tasks. It utilizes the power of the **ReActAgent** and **Llama-Index** framework to combine reasoning capabilities and specialized tool functions to automate and optimize various aspects of drug discovery.

## Key Features

### **🔬 Drug Discovery Task Functions**
DrugPilot covers the entire drug discovery lifecycle by implementing algorithms for the following key tasks:

- **💊 Drug-Cell Response Regression Prediction**  
- **⚙️ Drug-Cell Response Regression Optimization**  
- **💡 Drug-Drug Response Prediction**  
- **🧬 Drug Generation**  
- **📊 Drug Property Prediction**  
- **🛠️ Drug Synthesis Design**  
- **🧑‍🔬 Drug Target Affinity Classification Prediction**  
- **🎯 Drug Target Affinity Regression Prediction**

These tasks are designed to enable users to seamlessly integrate AI-driven solutions into their drug discovery pipelines.

### **🛠️ Agent Framework Enhancements**
Based on the **ReActAgent** architecture of **Llama-Index**, DrugPilot introduces several optimizations and enhancements to make it more robust for complex drug discovery workflows:

- **🔄 Optimized Output Parser**: Improves parsing of LLM outputs for higher accuracy and efficiency in task execution.
- **💬 Enhanced Feedback Mechanism**: Tailored feedback loop that improves error detection and provides corrective feedback during the reasoning process.
- **🔍 Focus Mechanism**: Ensures LLM remains focused on the original task throughout long conversations, avoiding task drift.
- **🧠 Memory Pool**:  
  - Addresses challenges related to large-scale data transmission.  
  - Automatically extracts and structures drug-related parameters for reuse in future tasks.  
  - Offers a user-friendly interface for viewing, modifying, and controlling the LLM's reasoning and decision-making process.

## **🚀 How It Works**
Users can input textual descriptions related to drug discovery, and DrugPilot will use its optimized agent framework to return the corresponding task results, leveraging its comprehensive suite of algorithms.

## **⚙️ System Requirements**
To run DrugPilot, you need to have the following packages installed:

| Package Name | Version |  
|--------------|---------|  
| llama-agents | 0.0.14  |  
| llama-cloud | 0.1.4   |  
| llama-index | 0.11.20 |  
| llama-index-agent-openai | 0.3.4   |  
| llama-index-cli | 0.3.1 |  
| llama-index-core | 0.11.20 |  
| llama-index-embeddings-openai | 0.2.5 |  
| llama-index-indices-managed-llama-cloud | 0.4.0 |  
| llama-index-legacy | 0.9.48.post3 |  
| llama-index-llms-ollama | 0.3.2 |  
| llama-index-llms-openai | 0.2.16 |  
| llama-index-multi-modal-llms-openai | 0.2.3 |  
| llama-index-program-openai | 0.2.0 |  
| llama-index-question-gen-openai | 0.2.0 |  
| llama-index-readers-file | 0.2.2 |  
| llama-index-readers-llama-parse | 0.3.0 |  
| llama-parse | 0.5.12 |  

## **🛠️ Dependencies for Drug Tools**

### Framework & Middleware Dependencies
```bash
conda install django==4.1
conda install mysqlclient==2.0.3
pip install celery==5.3.6
pip install eventlet==0.36.0
pip install django-cors-headers==4.3.1
pip install djangorestframework-simplejwt==5.3.1
pip install django-redis==5.4.0
```

### Algorithm Modules Dependencies
```bash
# PyTorch dependencies
conda install pytorch==1.13.1 torchvision==0.14.1 torchaudio==0.13.1 pytorch-cuda=11.7 -c pytorch -c nvidia
pip install torch==1.13.1+cu117 torchvision==0.14.1+cu117 torchaudio==0.13.1 --extra-index-url https://download.pytorch.org/whl/cu117

pip install torch-geometric==2.3.1
pip install ftfy==6.1.3
pip install regex==2023.12.25
pip install rdkit==2023.9.5
pip install networkx==3.1
conda install -c dglteam dgl-cuda11.7==0.9.1post1
pip install dgllife==0.3.2
pip install yacs==0.1.8
pip install sympy==1.12
pip install clip==0.2.0
pip install chardet==5.2.0

# torch_scatter for PyTorch-Geometric
pip install torch_scatter-2.1.0+pt113cu117-cp38-cp38-linux_x86_64.whl

pip install clip-anytorch==2.6.0
pip install easydict==1.13
pip install einops==0.8.0
pip install pubchempy==1.0.4
pip install pyemd==1.0.0
pip install dill==0.3.8
pip install fcd_torch==1.0.7
pip install pandas==1.5.3
pip install matplotlib
pip install h5py
pip install text2vec==1.2.9
```

## **🛠️ Installation & Setup**
To get started with DrugPilot, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-repo/drugpilot.git
    cd drugpilot
    ```

2. Install dependencies

3. Start using the DrugPilot framework by interacting with the API. For specific usage, please refer to main.py

## **📈 Usage**
To interact with DrugPilot, send textual descriptions related to drug discovery tasks via API calls, and DrugPilot will handle the rest by utilizing the eight core drug discovery functions. Each function is optimized for various drug discovery steps, from cell response prediction to drug generation.

## **🏁 Conclusion**
DrugPilot is designed to streamline the process of drug discovery by providing a scalable and efficient LLM agent framework. Its integration with the **Llama-Index** platform, combined with specialized tool functions and an optimized agent framework, allows researchers and pharmaceutical companies to accelerate the discovery of new drugs and optimize existing ones.

