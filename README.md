# Examples from Unleash The Power Of AI

### Requirements

## Installing Python

1. **Download Python:**
   - Visit the official Python website: python.org
   - Select the version appropriate for your operating system (Windows, MacOS, Linux/UNIX).
2. **Run the Installer:**
   - For Windows: Download and execute the installer.
     Make sure to check the box that says “Add Python to PATH” before installation.
   - For MacOS: Open the downloaded .pkg file and follow the instructions.
   - For Linux/UNIX: Python usually comes pre-installed.
3. **Verify Installation:**
   - Open your command line or terminal.
   - Type python --version (or python3 --version on some systems). You should see the Python version number if the installation was successful.
4. **Update pip (Python's package installer):**
   - In the terminal, run python -m pip install
     --upgrade pip.

## **Installing Jupyter Notebook (optional)**

While not mandatory, installing Jupyter Notebook can greatly
facilitate your learning and experimentation with Python and APIs. Jupyter
provides an interactive, web-based environment where you can write, run, and
visualize code in real-time, which is ideal for beginners.

**Install Jupyter** : After Python is installed, run:

```

pip install notebook
```

**in your command line or terminal to install Jupyter Notebook.**

**Launch Jupyter** : Enter **jupyter notebook** in your command line or terminal. This will open Jupyter in your web browser.

**Create a New Notebook** : In the Jupyter interface, create a new Python notebook to start writing your Python code.

## **Installing Necessary Libraries**

Please install the following Python’s libraries, as well:

```
python-dotenv
openai
requests
openai-whisper
ffmpeg
python-ffmpeg
pydub
```

Or simply run

```
pip install -r requirements.txt
```

## **Create a .env file to store your API_KEY**

**.env** file should have this line:

```
OPENAI_API_KEY='your secret key'
```
