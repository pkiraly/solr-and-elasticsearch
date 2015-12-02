# Apache Solr and Elasticsearch
## Introductory level workshop material 

This project contains a Jupyter Notebook, containing the material for my presentation at OpenTechSchool Göttingen (http://www.meetup.com/OpenTechSchool-Goettingen/events/226562971/). Jupyter (previously, and more knowingly IPython) Notebook provides a way for the demonstrator to run codes interactively in a browser. I chosed this technique for two reasons: 1) it is cool, and perfectly fits to the purpose, which is to show how one can interact with the REST APIs of the search engine 2) some weeks ago I had the privilege, that the inventor of the tool, Fernando Pérez (University of California, Berkely -- http://fperez.org/) showed me the basics.

The examples showed you the very basics. I did not use any wrapper library written in Python intentionally: I wanted to show the pure REST requests and responses, in order it should remain easily implementable in any other programming language.

To run the notebook first you have to install Jupyter: http://jupyter.readthedocs.org/en/latest/install.html.

Then

```
cd path/to/this/project
jupyter notebook
```

in your browser you will see the main menu of Jupyter notebook and you should click on this notebook. You should also install Solr and Elasticsearch, but that parts is covered in the notebook itself.

Happy searching!
