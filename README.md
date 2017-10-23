# ACAT2017
This repository container the proceedings submitted to accompany our poster at the 18th International Workshop on Advanced Computing and Analysis Techniques in Physics Research:

https://indico.cern.ch/event/567550/contributions/2628886/

The document has been submitted for internal review by the ATLAS collaboration here:

https://cds.cern.ch/record/2287286

## Building
To build the PDF you may use the included Dockerfile to build a `latex` container and use it as follows:

```
docker build --tag latex .
docker run -it --rm --volume ${PWD}:/opt/work latex pdflatex AtlasDynafed
```
