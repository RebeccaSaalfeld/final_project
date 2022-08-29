# Poetry Bot

For my final project of the Ironhack Data Analystics Bootcamp I decided to take the challenge and build a poetry bot. An AI that is able to write poems in the style of Mary Oliver. I had one week to accomplish that.  
I mostly followed a tutorial of the TensorFlow YouTube channel: Training an AI to create poetry - https://www.youtube.com/watch?v=ZMudJXhsUpY. And added a input field where the user can give a word which the AI use as a seed to write the poem on. Therefore I worked with *word embedding*. The AI picks some random words from Mary Olivers vocabulary and chooses the ones best fitting the meaning of the input word, using these worde in the poem as well. (Here is a nice article explaining word embedding and how to use spacy for it: https://towardsdatascience.com/creating-a-poems-generator-using-word-embeddings-bcc43248de4f).  
I tried this with poems from Mary Oliver but also with poems from Pablo Neruda. Feel free to play around and use the code.  
I tried to different models (m1 and m2). m1 is a neural network with one bidirectional LSTM layer. m2 has two LSTM layer and a dropout layer in between.

The data - about 100 poems from Mary Oliver and 130 from Pable Neruda - is from https://www.best-poems.net.

The AI has some minor issues that I want to fix in the future. For example it has some sequence of words that it prefers and spits out regularly. Apart from that it returns really nice poems with a special touch. It makes you think about the meaning, provokes your creativity and creates new images in your head.

Here a two examples I like a lot:

> sweetest one of those magical places  
> wing like the dreams of your body waking  
> the bird was saying anything i can't remember  

----

> seems one life task   
> fire is a thumb and  
> the world hold me  
> curtains us going on one hoof over the fire  

