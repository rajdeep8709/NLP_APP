version https://git-lfs.github.com/spec/v1
oid sha256:ae6ce23dc8ecfdb127e656d489e976ea0e8dd9561cba8894321d1cadc54a4b97
size 3814
This code base is a QA App using llama2 model and Gradio as a user interface for Question answering. In this QA App database can also be updated and start questioning on the same by uploading documents in pdf format. 

How to run this QA App on your local system.
  Step 1: Copy llama model "llama-2-7b-chat.ggmlv3.q8_0.bin" from this link "https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/tree/main" and copy in "models" folder.
  Step 2: Install library from reqirement.txt by using command "pip install -r requirements.txt"
  Step 3: Run the main.py file "python3 main.py"
  Step 4: Copy link from terminal and open in browser 
  Step 5: Start Questioning.
  
How to update your own documents for QA system.
  Step 1: Copy your pdf documents in "data" folder.
  Step 2: Run the Command db_build.py "python3 db_build.py" (make sure your app "main.py" is not running).

  
How to run the Same QA App using docker Container.
