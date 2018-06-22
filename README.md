## Inspiration
Began life as a project for my Neural Networks class. The idea was to see how well one could generate pleasant-sounding music using a Neural Network (a la Andrej Karpathy and his neural network-generated [Shakespeare sonnets](https://karpathy.github.io/2015/05/21/rnn-effectiveness/).

## What it does
Feeding the network musical data in ABC notation, it generates a sequence character-by-character, whose output is a musical composition in ABC notation. This output can be fed into an ABC-to-MIDI converter to produce an audible music file.

## How I built it
Neural network in PyTorch using LSTM layers.

## Accomplishments that I'm proud of
Generated music in ABC notation, solely through sequential generation of characters from a recurrent neural network.

Network consisted of LSTM layers for learning information about song structure, musical measures, and required headers.

## What I learned
Anything is possible.

## What's next for Machine-composed Music
Incorporating attention into the model, with the hopes that the network can learn things like repetition and melody.
