# BLIP-Search for your own images 

Create your own image database, and use the BLIP function to search for the first few image data in the database that are most similar to the search text and display them.  
There are some parts that need to be changed before executing the notebook in sequence.  

# Pre-installed  

```
pip install salesforce-lavis
pip install pillow
pip install mediapy
```

# Image path  

Change to your image folder path.

```
db_root = Path('Change there to your images path').absolute()
```

# Search  

Change the caption text to the text you want to search for.

```
#caption is the text you want to search for, change it and excute cell and below
caption = "text that you want to search"
```
