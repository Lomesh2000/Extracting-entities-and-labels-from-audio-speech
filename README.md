# Json file containing all the sentences and thier respective entities is mentioned above --- `new_result.json`
# We will extract entities and their respective labels from speech 
## Here we have a audio file i.e. `sales_call_telephone_marketers.wav`
### Audio file is converted into text using following modules:
#### 1) Module `Librosa` is used for loading and manupulate audio file
#### 2) Module `transormers` is used extensively : 
      Wav2Vec2ForCTC model and Wav2Vec2Tokenizer tokenizer is used from transformers
      
### In next half we are using Spacy module for entity extraction 

        
