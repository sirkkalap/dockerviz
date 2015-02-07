# dockerviz
Visualize local docker project dependencies

Dockerfiles depend on each other in simple dependency tree. Each Dockerfile can depend FROM a single parent.

I needed to quickly see what my dependecies are in a local collection of Dockerfiles. This project aims to render a simple
dependency graph from local Dockerfiles under given workdir.

