# RECTIGRAPH
A small tool to extract almost rectilinear roads from a graph (NetworkX, OSMnx)
The function to detect quasi-rectilinear contiguous edges in a directed graph seems quite efficient: on the London OSM graph with ~200K edges, it takes ~1s to identify all "meta-edges". It should work both for directed and undirected networkx graphs.
The code has not been thoroughly checked, so use with care. If you find important bugs, please report them here! Thanks.


Based on the "intersection-continuity-negotiation":
- Porta, S., Crucitti, P. & Latora, V. The network analysis of urban streets: a primal approach. Environ. Plann. B 33, 705–725 (2006)
- Viana, M., Strano, E., Bordin, P. et al. The simplicity of planar networks. Sci Rep 3, 3495 (2013) doi:10.1038/srep03495
