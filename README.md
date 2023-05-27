The Project report aims to develop bAbI chatbot of Facebook
AI Research which is organized towards the goal of automatic
text understanding and reasoning. Chatbots are frequently used
to improve the IT service management experience, which
delves towards self-service and automating processes offered
to internal staff.

A chatbot is generally created using LSTM -A
RNN(Recurrent Neural Network) model. RNN is a special kind
of neural network that is designed to effectively deal with
Sequential Data. LSTMs (Long-Short Term Memory) are
variants of RNN that solve Long Term Memory of the former.
They mitigate the problems of exploding and vanishing
gradients.

The Facebook bAbI has certain tasks. The aim is that each task tests a
unique aspect of text and reasoning, and hence test different
capabilities of learning models
.
The data-set comes already separated into training data (10k
instances) and test data (1k instances), where each instance has
a fact, a question, and a yes/no answer to that question.
Training Set Size: For each task, there are 1000 questions for
training, and 1000 for testing.

Example :
1 Mary moved to the bathroom.

2 John went to the hallway.

3 Where is Mary? bathroom

4 Daniel went back to the hallway.

5 Sandra moved to the garden.

6 Where is Daniel? hallway

Here lines 1,2,4,5 represent story, 3,6 represent questions related to
that story and their respected answers. The aim of chatbot is to predict
the correct answer for such questions in the test data set.
