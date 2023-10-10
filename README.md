<h1> Project Description</h1>
  This code base is a QA App using llama2 model and Gradio as a user interface for Question answering. In this QA App, documents in PDF format can be uploaded to update the database and ask new questions based on the updated information.

<h2>How to run this QA App on your local system.</h2>
  Step 1: Copy llama model "llama-2-7b-chat.ggmlv3.q8_0.bin" from this link "https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/tree/main" and copy in "models" folder.</br>
  Step 2: Install library from reqirement.txt by using command "pip install -r requirements.txt"</br>
  Step 3: Run the main.py file "python3 main.py"</br>
  Step 4: Copy link from terminal and open in browser</br> 
  Step 5: Start Questioning.</br>
  
<h2>How to update your own documents for QA system.</h2>
  Step 1: Copy your pdf documents in "data" folder.</br>
  Step 2: Run the Command db_build.py "python3 db_build.py" (make sure your app "main.py" is not running).</br>

  
<h2>How to run the Same QA App using docker Container.</h2>
