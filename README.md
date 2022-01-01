# rasa_waadachatbot# WAADAA.INSURE Chatbot Service

## Dependencies:
* `Rasa 3.0`

## Run the commands:

* Train Bot using .yml data: `rasa train`
* Run Bot on Shell: `rasa shell`
* Start Rasa server: `rasa run`

### Server RUN

* `rasa run -m models --enable-api`
* `python app.py`

## NLU and Core model training:

* `nlu.yml`: Contains the Intents to be used for NLU model.
* `domain.yml`: Contains Index of Intents, Bot Memory Slots and User Data Form as well as Bot response utterances.
* `rules.yml`: Contains basic response rules and User Data Form actions loop.
* `stories.yml`: Contains workflow for case data to train conversational core model.
