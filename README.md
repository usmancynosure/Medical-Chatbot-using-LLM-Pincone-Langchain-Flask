# Medical-Chatbot-using-LLM-Pincone-Langchain-Flask

## Project Setup

### 1. Create Project Structure

Run the following command in your Bash terminal (e.g., Git Bash):

```bash
bash template.sh
```
This will create the necessary folders and files for the project.

### 2. Conda Environment Setup

#### If using Anaconda Prompt or Miniconda Prompt (Recommended):

```bash
conda activate medibot
```

#### If using Git Bash or MINGW64:
If you see the error `CondaError: Run 'conda init' before 'conda activate'`, add the following line to your `~/.bashrc` or `~/.bash_profile`:

```bash
source /d/miniconda3/etc/profile.d/conda.sh
```
*(Adjust the path if your Miniconda is installed elsewhere.)*

Then restart your terminal and run:

```bash
conda activate medibot
```

### 3. Install Requirements

After activating the environment, install dependencies:

```bash
pip install -r requirements.txt
```

---
If you encounter any issues, please ensure you are using the correct terminal for your environment and that Conda is properly initialized.