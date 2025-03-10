# ai-assistant-personal-gui

## Overview
This project is a personal GUI assistant designed to help with various tasks. The repository contains the following main folders and files:

## Folders and Files
- **model_ollama/**: Contains models and related files for the Ollama integration.
- **gui_anythingllm/**: Contains files and configurations for the AnythingLLM integration.

## Getting Started
To get started with the project, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/ai-assistant-personal-gui.git
    ```

2. Create a name space:
    ```sh
    kubectl create namespace NS_NAME
    ```

3. Deploy the components to run the model
    ```sh
    kubectl apply -f model_ollama/
    ```


3. Deploy the GUI to configure the AI Assistant
    ```sh
    kubectl apply -f gui_anythingllm/
    ```


## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License.

