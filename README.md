# Test Graphs

## Format

In edgelist files each line has an edge listed as a space seperated pair of vertex names (usually numbers). An edgelist file for a 3-path would look something like

    1 2
    2 3

In position files each line has a vertex name and two coordinates, separated by spaces. A position file for a 3-path could look something like

    1 -1.0 0.0
    2 0.0 0.0
    3 1.0 0.0

## NetworkX

NetworkX has a variety of graph generators, including some common small example social networkx graphs. It also has a force based layout function, which was used to generate the position files.

 * Karate Club Graph: `networkx/kcg.edges` and `networkx/kcg.pos`

## OPTE

Subgraphs used in the internet mapping project at [http://www.opte.org/](). Edgelists are in `*.edges`, positions are in `*.2D.coords`. 

 * `opte_data/1105841711/1105841711.edges`, `opte_data/1105841711/1105841711.2D.coords`
 * `opte_data/1069646562/1069646562.edges`, `opte_data/1069646562/1069646562.2D.coords`
 * `opte_data/1069524880/1069524880.edges`, `opte_data/1069524880/1069524880.2D.coords`

## Further Notes

More graphs coming
