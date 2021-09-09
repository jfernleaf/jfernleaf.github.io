---
title: "Understanding How Self-Fulfilling Prophecy Plays a Role in Conversation with Language Model"
collection: talks
type: "Lightning Talk"
permalink: /talks/2021-08-12-stanford-surf
venue: "Stanford School of Engineering"
date: 2021-08-12
location: "Virtual via Zoom"
---
You are all invited! My talk will take place at 2:15pm, August 12, 2021. If you are planning to come please fill out this [google form](https://forms.gle/8b1rYL3yEFxdRXEg6) to acknowledge the recording of the session as well as request any anticipated accommodations as you need. ![With the rise of artificial intelligence, chatbots have become more generative, meaning that they are capable of learning from input queries and responding to them on the fly. 56.4% of US adults use voice assistants like Apple Siri, Amazon Alexa, Google Assistant and Samsung Bixby that are powered by generative language models.Generative chatbots are trained on human-human conversations, where self-fulfilling prophecy is proven to play a role. For example, You might believe, "This person is nice and accepting" > You go out of your way to start a conversation, and act warm and friendly around them > They see you seem to like them and are friendly in response > You think "Ah, they're as nice as their reputation said they'd be." This led us to wonder if a language model like GPT-3 would mimic the way humans talk to it and potentially in line with the beliefs humans have about it. Specifically, if humans talk to it nicely, would GPT-3 respond to it nicely And if humans talk to it in a way that can lead to personal attack, would GPT-3 learn that and derail the conversations. To study this, we take 200 conversation starters that are civil (half of them come from the conversations that eventually derail and end with personal attack while the other half come from the ones that remain civil) and let GPT-3 complete the conversations. Then we analyze the generated conversations with Evaluative Lexicon, Valence Aware Dictionary and sEntiment Reasoner, and Perspective API to get psycholinguistic measures of emotionality, extremity, valence, and toxicity. We found that GPT-3 completes the conversations with a more overall negative tone than the conversation starters. For conversation starters that have a tendency to lead to personal attack, GPT-3 completes conversations with more negative sentiment, higher toxicity, insult, threat, and profanity scores than for the conversation starters that do not have such tendency. Our findings show that GPT-3 is capable of continuing the conversation with a similar tone that it was started with, suggesting the possibility of self-fulfilling prophecy. To fully verify the whole loop of self-fulfilling prophecy, we want to further explore whether GPT-3’s responses reinforce human’s beliefs and how self-fulfilling prophecy amplifies over time in the future. Since self-fulfilling prophecies can lead to unwanted biased outcome of the conversations, we want to eventually perform intervention analysis to see how much control we have over self-fulfilling prophecy phenomenon and come up with guidelines on how to mitigate the phenomenon.I would like to take this time to thank the Stanford Undergraduate Research Fellowship Program for support and funding in this project, as well as, National Science Foundation and Apple Scholars Fellowship. I would like to give a special thanks to Prof. Bernstein, Joon,, Ranjay, Mitchell, and the Stanford HCI Group for providing guidance and feedback throughout this project.](./images/SURF_poster.png)

With the rise of artificial intelligence, chatbots have become more generative, meaning that they are capable of learning from input queries and responding to them on the fly. Generative chatbots are trained on human-human conversations, where self-fulfilling prophecy is proven to play a role. An example of self-fulfilling prophecy might be when you believe that the other party is nice and accepting then go out of your way to start a conversation and act friendly around them. The other party then see you seem to like them and act friendly in response, leading you to think that the other party lives up to their nice reputation. However, the resulting desirable interaction is mostly a result of your initial belief.

Our research focuses on understanding if a language model like GPT-3 can mimic the way humans talk to it and potentially in line with the beliefs humans have about it, which can help us understand if self-fulfilling prophecy phenomenon can happen during such interaction. Understanding it can really help us take control and moderate the human-chatbot interactions to ensure that they abide by specific community guidelines.