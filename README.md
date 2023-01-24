# Understanding and Predicting User Satisfaction with Conversational Recommender Systems


This repository consist of resources created for the following paper:


        Understanding and Predicting User Satisfaction with Conversational Recommender Systems
  

## Dataset Description

This data consist of annotations at the turn and dialogue level.

### Turn-level Annotation

At the turn level we annotate each turn with two dialogue aspects: *relevance* and *interestingness* and turn-level satisfaction. This data is in the file *annotated_turns.csv*.

Each turn consist of four utterances: two previous utterances as context, current utterance(system utterance) and the next user utterance. 

The labels are relevanceK, interestingessK and overallK, where K is the turn number.

Each turn was annotated with atleast three annotators.


### Dialogue-level Annotation

At the Dialogue level, a dialogues is annotated on four dialogue aspects namely: *understanding*, *task completion*, *interest arousal*, and *efficiency* and finally overall user satisafction for each turn is annotated. This data is in the file *annotated_dialogues.csv*

Each dialogue was annotated by atleast three annotated, and each dialogue has a unque *ConvId*. A dialogue annotated by multiple annotators share the same unique Id.

Turns sampled from a dilaogue have the same unique Id.

#### Dataset Statistics


| level        | count           | 
| ------------- |:-------------:|
| Turns     | 600 |
| Dialogues     | 200      |   



