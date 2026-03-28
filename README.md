# AI-Item-Scanner
This small program uses **Python** and **Gemini AI** to perform a scan of an image, list the items detected in that image, estimate the price for those items, calculate the total cost of the items, and print a receipt. Developed using **Google Colab**. This program serves as a proof of concept, and is my own personal demo on how something like this can be done using Gemini.

Currently uses Gemini 2.5 Flash Lite.

An example of the code successfully running is shown in the `ShoppingList.ipynb` file.

## Important
* When using this program, you will need to obtain, and link your own Gemini API Key to the google colab notebook for it to properly run. You can obtain one through **Google AI Studios**.
* When using this program, you may get an error mentioning "429 token limit reached". This indicates either...
   1. The Gemini model version is deprecated, and a new one must be used. This can be fixed by changing the value of `genModel` towards the beginning of the program, however, this can also cause code instability.
   2. You reached your Gemini token limit. This is most common when using the free tier version of Gemini, and often requires you to wait until you recieve more tokens. You can check your token usage in Google AI Studios.

##
You can access the notebook to examine the code by using the "Open in Colab" button within the shared file, or by using this link: [https://colab.research.google.com/github/Turbostar123/AI-Item-Scanner/blob/main/ShoppingList.ipynb](https://colab.research.google.com/github/Turbostar123/AI-Item-Scanner/blob/main/ShoppingList.ipynb)
