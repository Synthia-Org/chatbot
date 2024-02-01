# chatbot
Repository containing bot for the Synthia website

<hr>


### Commands

#### Step 1
```
sudo apt install python3 python3.10-venv
```

#### Step 2
```
python3 -m venv rasa_env
```

#### Step 3
```
source rasa_env/bin/activate
```

#### Step 4
```
pip install rasa
```

#### Step 5
```
rasa init --no-prompt
```

#### Step 6
```
rasa train
```

#### Step 7
```
rasa run --enable-api --cors "*" -m models/model_name.tar.gz --port 5005
```
