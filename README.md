# Tiny Neural Network Studio (v4)

Tiny Neural Network Studio is a browser based learning tool.
It visualises how a small neural network works and how it learns from data.
It is designed for architecture and built environment students.

## Live app
https://p4303997-arch.github.io/tiny_neural_network_studio/

## Repository
https://github.com/p4303997-arch/tiny_neural_network_studio

## What this app teaches
The app teaches what a neuron does during a forward pass.
The app teaches what weights and bias mean as learned priorities.
The app teaches how training updates weights to fit labelled examples.
The app teaches why extra hidden neurons increase capacity and also complexity.
The app teaches how design reasoning can be encoded as labelled targets.

## Key features
You can change sun intensity and wind exposure with sliders.
You can click nodes and links to see pop up explanations.
You can edit weights and bias directly and see immediate effects.
You can paste a dataset and train the network in the browser.
You can view a loss curve to see learning progress.

## How to use
Open the live app link in a modern browser.
Move the input sliders and watch the output change.
Click a neuron to read an explanation and see live values.
Switch to training mode and load a dataset.
Run training and watch the loss reduce across epochs.
Increase hidden critics to 3 and retrain.
Discuss why more capacity is a cost as well as a benefit.

## Training data format
Training data is comma separated values.
Each line is one example.

**Format**
sun,wind,target

**Ranges**
sun is between 0 and 10.
wind is between 0 and 10.
target is between 0 and 1.

**Example**
9.6,7.8,0.87
0.5,2.4,0.05

## Suggested studio exercise
Pick a real site and describe its sun and wind conditions.
Agree on a consistent rule for shading urgency labels.
Create 20 to 60 labelled examples.
Train the network and inspect the learned weights.
Explain which input became the strongest driver and why.

## Deployment
This repository is hosted with GitHub Pages.
The entry file is `index.html`.
To publish an update, commit changes and push to the default branch.

## Credits
Development used iterative prompt based coding workflows.
Development was assisted by ChatGPT 5.2.
Concept framing was informed by the Applied Generative Artificial Intelligence for Digital Transformation course at MIT Professional Education.

## License
MIT License.
See `LICENSE`.
