# ps9_bits_n_bytes

#Lets start by making a virtual environment env<br>
#SO we followed the following steps to make it
1.Try to open cmd from a particular folder where you need to run the program
  Install Packages(libraries)
  pip install virtualenv 
  pip install virtualenv env
2.Lets activate the env in our folder
  for activating it
  ....env\scripts\activate
3.after that open the folder in any idle
  then install the following packages
  pip install flask
  pip install chatterbot
  pip install chatterbot-corpus
  and try running the chatbot.py and app.py files int idle
if it throws some error in packages then please try to satisfy the requirements
if the error is on time.clock() then please redirect to that file and change time.clock to time.perf_counter/time.process_time
