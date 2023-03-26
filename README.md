# AI-AutoStoryTelling
AI-AutoStoryTelling using pre-trained deep neural network



We can create and train our own deep learning model architecture as per Plan-And-Write 
paper. which requires too much work and costs for hardware usage because to train language 
model. Or, we can leverage pre trained state of the art language models to start with.(such as 
Transformer or GPT etc.)


• If we choose this path, we phrase the story title and words-to-use as a writing prompt and the 
model will continue to finish the story. Here, we can use two NLP techniques: 
• Auto text summarization and Keyword extraction. Idea is to extract a summary or a few key 
phrases from the original text. While training, the model learns to expand the summary or the 
key phrases to restore the original text.


• Using this method we can build our model fast using pre-trained open-source state of the art 
language model, which delivers diverse and reasonable results. Here, we are building a 
solution from scratch tweaking the information/study done in ‘Plan-and-Write’ paper.



 --------------------------------------------------    Future Work    -------------------------------------------------
 
Following work above completed by finetuning pretrained T5-base Model. with just 40k training sample data. This is the base line model and delivering good results preserving context of the generated story, as per the model input. 
And following model can be funed further to deliver best result by tuning its hyperparameter or along with hyperparameter we can try using T5-Large to generate more realistic stories.
