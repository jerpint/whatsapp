# whatsapp
Analysis of whatsapp conversation history.

First, clone the repository :

`cd && git clone https://github.com/jerpint/whatsapp.git`

Go to any Whatsapp group chat and send it to yourself by email. Save the file `convo.txt` to the same directory as the cloned project.

To run it, open the jupyter notebook and run it cell by cell :

```
cd ~/whatsapp
jupyter notebook
```

You should then be able to run every cell sequentially. 

This notebook will allow you to compute different metrics, such as times of conversations and interaction matrices. They are all explained inline in the markdown of the notebook.

# Requirements

You should have jupyter notebook installed with python 3.* as well as `pandas`, `numpy`, `matplotlib` as well as `wordcloud` which can all be installed using `pip`.
