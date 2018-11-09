## Graph Model Export

After some research this is what was inferred.
  - Frontend:
    - A **Graph** option could be added to the list that appears when the export button is clicked.

  - Backend:
    - Models first have to be filtered, by removing duplicate blocks (this could be textually represented in the graph).
    - This filtered model could then be converted to proper graph by using a library like [MxGraph](https://github.com/jgraph/mxgraph).
    - The graph can be sketched on canvas and later converted to an image.
