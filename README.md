![download](https://user-images.githubusercontent.com/52428892/211189605-299b54d7-341a-4529-9a0e-e535a189d185.png)




1Put cls and sep on the senten column, separating each sentence from another

2 Make a toknizer for each sentence, dividing it into better words than split

3 Make a paddig so that when the maxlegnth of the sentences is specified, the rest of the zeros will be added

4 I'd work so that he puts an I'd number for each word Feature that turns into numbers

5 Make a mask that searches for the largest zero, so this feature is a task B1

After that, convert the data to a tensor, so that the model is easy to handle, and the tensor is fine
Then call on a model that has a specific format in pytorch where the dataloador is
Accuracy has the particular form flat accurac
