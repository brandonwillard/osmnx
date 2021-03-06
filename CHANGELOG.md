# Change log

## 0.5.1 (2017-05-12)
  - Functionality to clean-up and consolidate complex intersections
  - Let save_gdf_shapefile save building footprint GeoDataFrames
  - Set node color correctly in figure-ground diagrams

## 0.5 (2017-04-25)
  - add elevation module to get node elevations and street grades
  - new color sequence creation and conversion functions in plot module
  - new function to get a path's edge attribute values
  - gracefully handle subpolygons that are invalid or have zero area
  - make truncate_graph_polygon work on projected graphs
  - plot_shape accepts a color or a list of colors
  - make all requests to Overpass API set custom user-agent and referer
  - rewrite algorithms to convert multidigraphs to multigraphs 

## 0.4.1 (2017-04-01)
  - fix load_graphml so we can save a graph again after loading it
  - fix load_graphml so edge oneway attribute is not always set to True
  - buildings module gets buildings stored in OSM as relations as well as ways
  - fix figure-ground diagram saving to make perfect square and smooth joints
  - add optional graph argument to plot_figure_ground
  - suppress jupyter notebook deprecation warnings

## 0.4 (2017-03-01)

  - plot entire networks with folium
  - plot routes on top of networks with folium
  - vectorize all great circle calculations
  - new geocode function in utils
  - remove geopy dependency
  - refactor modules
  - simplify before truncating by distance when getting graph by point and network distance
  - project geometries, GeoDataFrames, and graphs to a passed-in CRS
    
## 0.3.1 (2017-02-15)

  - clean up docstrings throughout
  - remove network code vestiges from buildings.py

## 0.3 (2016-01-29)

  - add route plotting with folium
  - add downloading and visualization of building footprints
  - updates for compatibility with matplotlib 2.0

## 0.2.2 (2017-01-20)

  - fixes for compatibility with networkx 2.0's new API
  - make png default image save format
  - figure-ground plots collect street network from a wider area

## 0.2.1 (2017-01-11)

  - add license file to dist package

## 0.2 (2017-01-10)

  - refactor modules
  - add graph to GDF and GDF to graph functions
  - add encoding argument to save_graph_shapefile
  - add unit tests and continuous integration  

## 0.1 (2016-12-19)

  - add street width attribute for ways from OSM

## 0.1b2 (2016-11-29)

  - make simplification error messages explicit
  
## 0.1b1 (2016-11-28)

  - process land use and area tags from OSM
  - make intersection error messages clear
  
## 0.1a1 (2016-11-07)

  - first pre-release
