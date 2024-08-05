# ML Ops Labs Set Up

## Lab 0: Setup 

Follow these steps to set up your environment for the tutorials:

1. **Install Python 3.11 with Homebrew**

    Open your terminal and run the following command:
    ```sh
    brew install python@3.11
    ```

2. **Create a Virtual Environment**

    Navigate to the repository directory and create a virtual environment using Python 3.11:
    ```sh
    python3.11 -m venv venv
    ```

3. **Activate the Virtual Environment**

    Activate the virtual environment:
    ```sh
    source venv/bin/activate
    ```

4. **Upgrade pip**

    Upgrade the pip library to the latest version:
    ```sh
    pip install --upgrade pip
    ```

5. **Install Requirements**

    Install the necessary packages from the `requirements.txt` file:
    ```sh
    pip install -r requirements.txt
    ```

6. **Ensure Jupyter Uses Python 3.11**

    Install the IPython kernel and create a new kernel for Python 3.11:
    ```sh
    ipython kernel install --user --name=python3.11
    ```
   

## Lab 1: Deploying a Model as a web service and accessing it from a client

1. **Activate your environment and open jupyter to begin the lab**
    ```sh
    source venv/bin/activate
   jupyter lab
    ```