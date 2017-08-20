# viz-experiments
---
In order to get acquainted with D3.js I explored creating simple visualisations with algorithms.

## Baravelle Spiral

The baravelle spiral is created by placing squares in one another with each new square's vertices placed at the midpoints of the sides of the previous square. I considered instead the triangles that form as part of this process to better understand how to create the spiral pattern.

Here is a little working out, which can help to explain the code.

![]()

### Usage

* Download the baravelle.html page.
* Run a basic server (I  use Python for this).
  
```Python
# Python 3
python -m http.server

# Python 2
python -m SimpleHTTPServer
```
TODO  
[ ] Animate the spiral formation.