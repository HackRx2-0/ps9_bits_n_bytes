# ps9_bits_n_bytes

Lets start by making a virtual environment env<br>
SO we followed the following steps to make it<br>
1.Try to open cmd from a particular folder where you need to run the program<br>
  %nbspInstall Packages(libraries)<br>
  pip install virtualenv<br>
  pip install virtualenv env<br>
2.Lets activate the env in our folder<br>
  for activating it<br>
  ....env\scripts\activate<br>
3.after that open the folder in any idle<br>
  then install the following packages<br>
  pip install flask<br>
  pip install chatterbot<br>
  pip install chatterbot-corpus<br>
  and try running the chatbot.py and app.py files int idle<br>
if it throws some error in packages then please try to satisfy the requirements<br>
if the error is on time.clock() then please redirect to that file and change time.clock to time.perf_counter/time.process_time<br>
