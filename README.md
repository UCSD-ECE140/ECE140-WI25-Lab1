# ECE 140A Lab 1: Software Setup and Installation

If you've already completed Steps 1 and 2, you can skip to Step 3. Please help your teammates if they are stuck!

## Step 1: Install Git

1. Refer to [Tutorial 1](https://docs.google.com/document/d/1vMTIXIA-o72L0PdaAxDn55p51FY9HCRakYuqv7tp9yA/edit?tab=t.0#heading=h.kk1966kbedef) of Tech Assignment 1 for instructions on how to install Git. You only need to read the **first page** of this tutorial for the sake of this lab exercise. You will complete the rest later on.
2. Verify that Git has been installed by running the following command in your terminal:
   ```bash
   git --version
   ```
   If Git has been installed correctly, you should see the version number of Git displayed in the terminal.
3. Now, let's clone this repository to your local machine. Go to a suitable directory, and run the following command in your terminal:
   ```bash
   git clone https://github.com/UCSD-ECE140/ECE140-WI25-Lab1.git
    ```
4. Navigate to the cloned repository by running the following command in your terminal:
   ```bash
   cd ECE140-WI25-Lab1
   ```
5. Now, run `ls` in your terminal to see the contents of the repository. You should see a `main.py` file, a `requirements.txt` file, and a `README.md` file.

## Step 2: Install Python

1. Refer to [Tutorial 2](https://docs.google.com/document/d/1uyR9mASscxhrd-Daeq9z-LWqoLI-N32G3E5OKPy9JQc/edit?usp=sharing) of Tech Assignment 1 for instructions on how to install Python, VSCode, and work with virtual environments.
2. Check that Python has been installed correctly by running the following command in your terminal:
   ```bash
   python --version
   ```
   If Python has been installed correctly, you should see the version number of Python displayed in the terminal.
   **Note**: Depending on your installation, you might need to use `python3` instead of `python`.


## Step 3: Install Required Packages

Once you've activated your virtual environment following the instructions in Tutorial 2, you can install the required packages by running the following command in your terminal:

```bash
pip install -r requirements.txt
```

## Step 4: Run the Python Script

Now that you have installed the required packages, you can run the Python script by running the following command in your terminal:

```bash
python main.py
```

If you get an output like the following, then your software setup is complete:

```
INFO:     Will watch for changes in these directories: ['/Users/gk/Desktop/ECE140A/ECE140-WI25-Lab1']
INFO:     Uvicorn running on http://0.0.0.0:8000 (Press CTRL+C to quit)
INFO:     Started reloader process [80102] using WatchFiles
INFO:     Started server process [80110]
INFO:     Waiting for application startup.
INFO:     Application startup complete.
```

## Step 5: Viewing the `/docs` Endpoint and Gradescope submission

Open your browser and navigate to http://0.0.0.0:8000/docs. You should see a page that displays the API documentation for the `/docs` endpoint. This is the FastAPI Swagger UI, which provides a user-friendly interface to interact with the API. It allows you to test the API endpoints directly from the browser and indicates what routes are available.

**Note**: On Windows machines, you may need to use http://localhost:8000/docs instead.

Take a screenshot of what you see when opening the link above and submit it to Gradescope. 