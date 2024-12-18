# Python for AI

From here I can learn python from Andrew NG course Ai python for beginners

https://www.deeplearning.ai/short-courses/ai-python-for-beginners/

## Google Colab Setup

We will be using Google Colab to learn Python and develop a future-proof programming skill set. Follow these simple steps to set up your environment, then move on to course_1_basics.

#### 1. Create a Folder in Google Drive:

1. Open Google Drive.
2. Create a folder called python_utils.
3. This folder will be used to store utility script you'll use throughout the course.

#### 2. Download the helper_functions.py File:

1. Download the helper_functions.py file from this step.
2. Upload the helper_functions.py file into the python_utils folder in your Google Drive.

#### 2. Mount Google Drive in Google Colab:

To access the files you upload to Google Drive, you'll need to mount your drive in Colab. Use the following code snippet to do this:

```python
from google.colab import drive
drive.mount('/content/drive')

# Change directory to where 'python_utils.py' is stored
%cd /content/drive/MyDrive/python_utils/

# Import the python_utils module
from helper_functions import *
```

#### 3. Add Gemini API key and Try the uploaded file functions

From [Google AI Studio get your API KEY](https://aistudio.google.com/app/apikey) and add a new environment variable GOOGLE_API_KEY in notebook.

Now import and try the function from uploaded file.

````
# Now you can call functions
print_llm_response("What is the capital of France?")```
````

### Course 1: Basics

- L1: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/panaversity/learn-cloud-native-modern-ai-python/blob/main/04_natural_language_programming/02_ai_python_for_beginners/course1_basics/Lesson_4/Lesson_4.ipynb)

