# Redefine the Diversity of image Captioning

This is the umich EECS 598 Deep Learnig Final Project. 


### Mapping from image to text is essentially “one-to-many”. The captions, in our opinion, can diverse in three dimensions:
1. Content: objects or regions to describe
2. The level of Detail: richness of captions to describe the content, usually reflected by length of generated sentences
3. Form: variety of sentence structure or word choice, under constraint of the same content and level of detail
In this project we propose a model that is able to generate various captions for an image diverse in the three aspects.

### Contribution

1. New model for diverse caption generation
We introduce a new model architecture that is able to generate diverse captions in terms of content, detail and form.
2. Novel Multimodal Similarity Loss
3. We introduce a novel multimodal similarity loss to measure difference between image feature and text with the following advantages.
a) It can deal with similarity between multiple subregions of image with text.
b) It achieved better performance than previous metrics. Spot problems when using Language Model as criterion
We figured out why the LM failed when used as a criterion training decoder, and give future directions for solving this issue.

Thank you for my other team members' contribution. They are Chuan Cen, Yuan Liang, Ruoyao Wang, Feiyi
