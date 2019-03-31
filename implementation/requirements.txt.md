### Communcation 
Between Each Notebook & JupyterLab  
- Pass images from Notebooks to Thumbnails in Sidebar
- Pass state from Notebooks to Jupyterlab Server (State here meaning which have been executed).
- Jupyterlab Server / Client controlling synchronous (between forks) execution of cells.

### Cell Sharing / Search
Database of cells 
- local for user
- shared between users

Cell Metadata
- title, description, keywords, tooltip
- these need to be shown correctly in viewer (can insert fake cells and use markdown renderer?)

### Notebook Templates
- What exactly are the use-cases?
- Do we have a tool for programmitcally generating notebooks.
  - This also has the [spikeforest](https://github.com/flatironinstitute/spikeforest) use case
  - Since ipynb is json we could also use [json templating engines](https://github.com/vmware/json-template-engine). Or write our own.
