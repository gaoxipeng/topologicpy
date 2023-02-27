# topologicpy

<img src="https://topologic.app/wp-content/uploads/2023/02/topologicpy-logo-no-loop.gif" alt="topologicpy logo" width="250" loop="1">

# A Hierarchical and Topological Modelling and Spatial Analysis Library for Architecture

## Introduction
Welcome to topologicpy (pronounced the same as apple pie). topologicpy is a free and open-source python 3 implementation of [Topologic](https://topologic.app). Topologic is a powerful software modelling and spatial analysis library that revolutionizes the way you design architectural spaces, buildings, and artefacts. Topologic's advanced features enable you to create hierarchical and topological 3D representations that offer unprecedented flexibility and control in your design process. With Topologic, you can achieve your design vision faster and more efficiently than ever before. With the integration of geometry, topology, information, and artificial intelligence, Topologic replaces Building Information Models (BIM) with Building *Intelligence* Models.

Two of Topologic's main strengths are its support for *defeaturing* and *encoded meshing*. By simplifying the geometry of a model and removing small or unnecessary details not needed for analysis, defeaturing allows for faster and more accurate analysis while maintaining topological consistency. This feature enables you to transform low-quality, heavy BIM models into high-quality, lightweight representations ready for rigorous analysis effortlessly. Encoded meshing allows you to use the same base elements available in your commercial BIM platform to cleanly build 3D information-encoded models that match your exacting specifications.

Topologic's versatility extends to entities with mixed dimensionalities, enabling structural models to be represented coherently. Lines can represent columns and beams, surfaces can represent walls and slabs, and volumes can represent solids. Even non-building entities like structural loads can be efficiently attached to the structure. This approach creates a lightweight model that are highly compatible with structural analysis simulation software.

Topologic's graph-based representation makes it a natural fit for integrating with Graph Machine Learning (GML), an exciting new branch of artificial intelligence. With GML, you can process vast amounts of data and extract valuable insights quickly and accurately. Topologic's intelligent algorithms for graph and node classification take GML to the next level by using the extracted data to classify building typologies and complete missing information in building information models. This integration empowers you to leverage the historical knowledge embedded in your database and make informed decisions about your current design project. With Topologic and GML, you can streamline your workflow, enhance your productivity, and achieve your project goals with greater efficiency and precision.

Experience Topologic's comprehensive and well-documented Application Protocol Interface (API) and enjoy the freedom and flexibility that Topologic offers in your architectural design process. Topologic uses cutting-edge C++-based non-manifold topology (NMT) core technology ([Open CASCADE](https://www.opencascade.com/)), python bindings, and optional visual data flow programming (VDFP) plugins for popular BIM software. With Topologic, you can easily interact with the software in various ways to perform design and analysis tasks. Plus, Topologic’s open-source philosophy means that your information is yours and is never trapped. Topologic includes several methods for data transport including IFC, OBJ, BREP, HBJSON, CSV, and serializing through [Speckle](https://speckle.systems/).

Join the revolution in architectural design with Topologic. Try it today and see the difference for yourself.

## Installation
topologicpy can be install using the **pip** command as such:

`pip install topologicpy --upgrade`

## Prerequisites

topologicpy depends on the following python libraries which will be installed automatically from pip:

<details>
<summary>
<b>Expand to view dependencies</b>
</summary>
* [numpy](http://numpy.org) >= 1.24.0
* [scipy](http://scipy.org) >= 1.10.0
* [plotly](http://plotly.com/) >= 5.11.0
* [ifcopenshell](http://ifcopenshell.org/) >=0.7.9
* [ipfshttpclient](https://pypi.org/project/ipfshttpclient/) >= 0.7.0
* [web3](https://web3py.readthedocs.io/en/stable/) >=5.30.0
* [openstudio](https://openstudio.net/) >= 3.4.0
* [lbt-ladybug](https://pypi.org/project/lbt-ladybug/) >= 0.25.161
* [lbt-honeybee](https://pypi.org/project/lbt-honeybee/) >= 0.6.12
* [honeybee-energy](https://pypi.org/project/honeybee-energy/) >= 1.91.49
* [json](https://docs.python.org/3/library/json.html) >= 2.0.9
* [py2neo](https://py2neo.org/) >= 2021.2.3
* [pyvisgraph](https://github.com/TaipanRex/pyvisgraph) >= 0.2.1
* [specklepy](https://github.com/specklesystems/specklepy) >= 2.7.6
* [pandas](https://pandas.pydata.org/) >= 1.4.2
* [scipy](https://scipy.org/) >= 1.8.1
* [dgl](https://github.com/dmlc/dgl) >= 0.8.2

</details>

### Binaries

Download the latest Release binaries from the Releases link found on the right side of this [page](https://github.com/wassimj/topologicpy/releases).

## Installation

1. After you download the ZIP file, extract the topologicpy folder.
1. Place the topologicpy folder at a location that your python system can find.

## How to use
1. Open your favourite python editor ([jupyter notebook](https://jupyter.org/) is highly recommended)
1. Type 'import topologicpy'
1. Start using the API

## API Documentation
API documentation can be found at [https://topologic.app/topologicpy_doc/topologic_pdoc/](https://topologic.app/topologicpy_doc/topologic_pdoc/)
