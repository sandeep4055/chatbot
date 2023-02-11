# Chatbot

# What is Rasa?
<li>Rasa is a tool to build custom AI chatbots using Python and natural language understanding (NLU). Rasa provides a framework for developing AI chatbots that uses natural language understanding (NLU). It also allows the user to train the model and add custom actions.</li>
<img src="images/rasaachitecture-660x419.png" src="chatbot_image">

## Installation of Rasa  on windows
<a href="https://rasa.com/docs/rasa/2.x/installation/">link for installation guide </a>

# Documentation Rasa :
<li>Rasa uses YAML as a unified and extendable way to manage all training data, including NLU data, stories and rules.</li>

<h1 style="text-align: center;">Terminology</h1>
## Intent
<li>In a given user message, the thing that a user is trying to convey or accomplish (e,g., greeting, specifying a location).</li>

## Entities
<li>
Keywords that can be extracted from a user message. For example: a telephone number, a person's name, a location, the name of a product.
</li>

## Action
<li>A single step that a bot takes in a conversation (e.g. calling an API or sending a response back to the user).</li>

## Annotation
<li>Adding labels to messages and conversations so that they can be used to train a model.</li>


## Training Data folder High-Level Structure#
<li>Each file can contain one or more keys with corresponding training data. One file can contain multiple keys, but each key can only appear once in a single file. The available keys are:</li>

<ol>
<li>version</li>
<li>nlu</li>
<li>stories</li>
<li>rules</li>
</ol>



