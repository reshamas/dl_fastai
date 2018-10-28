# dl_fastai


## Get to Jupyter Notebook
- Go to localhost (run Jupyter Notebook):  
http://localhost:8080/tree

doc(interp.plot_top_losses)
- prediction, actual, loss, probability it was predicted
- Don't be afraid to look at the source code.
- confusion matrix, if you have lots of classes, don't use confusion matrix.  use interp.most_confused. 
- `unfreeze`:  please train the whole model
- if you run out of memory, use a smaller batch size
