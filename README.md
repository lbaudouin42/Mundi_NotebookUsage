# ------------------------------------------------------------------------------------------
#
#                            Welcome to Mundi Jupyter Notebook
#
# ------------------------------------------------------------------------------------------

#  /!\ Note that:
#          - your session will stop after a few minutes of inactivity,
#          - only elements in 'work' directory can be saved.

- Folders content:
'/lib/'    : Contains libraries. It is Read Only.
             Mundi library. 
             Based on 'OWSLib' https://geopython.github.io/OWSLib/: Python package compliant 
             with Open Geospatial Consortium (OGC) web service (hence OWS) interface standards, 
             and their related content models.
             CAMS (Copernicus Atmosphere Monitoring Service) library.
             CMEMS (Copernicus Marine Environment Monitoring Service) library.

'/public/' : Contains Notebook examples. It is Read and Executable Only.      

            - ------------------------------------------------------------------------------
            | Notebook name           | Description                                        |
            - ------------------------------------------------------------------------------
            | mundi_data_metadata     | Available data & metadata on Mundi                 |
            - ------------------------------------------------------------------------------            
            |                         | Web services. Discovery and usage examples:        |
            |                         |                                                    |            
            | mundi_csw               |    Catalogue Service Web                           |
            |                         |                                                    |
            | mundi_wcs               |    Web Coverage Service                            |
            | mundi_wfs               |    Web Feature Service                             |
            | mundi_wms               |    Web Map Service                                 |
            | mundi_wmts              |    Web Map Tile Service                            |
            |                         |                                                    |
            - ------------------------------------------------------------------------------
            | mundi_opensearch        | Examples of opensearch requests                    |
            - ------------------------------------------------------------------------------
            | mundi_gdal              | Visualisation of an image from Toulouse as         |
            |                         | an histogram from its raster.                      |
            - ------------------------------------------------------------------------------
            | mundi_exceptions        | Examples of Mundi raised exception                 |            
            | mundi_video             | Just for fun!                                      |
            - ------------------------------------------------------------------------------
            | mundi_country_polygon   | Example of how to get and visualize polygon,bbox   |
            |                         | and a geojson file from a country name             |
            | mundi_wms_city_polygon  | Example of how to get and visualize polygon, bbox  |
            |                         | and a satellite image from a city name             |
            | mundi_shapefile         | Example of how to create, read, and display a      |
            |                         | shapefile on a map                                 |
            - ------------------------------------------------------------------------------
            |                         | CAMS web services. Discovery and usage examples:   |
            |                         |                                                    |            
            | cams_europe_services    | Usage examples of Web Map Service, Web Coverage    |
            |                         | Service and Download API for Europe                |
            | cams_ecmwfapi           | Usage example of ECMWF api to download and         |
            |                         | display CAMS data                                  |
            |                         |                                                    |
            - ------------------------------------------------------------------------------
            |                         | CMEMS web services. Examples of interaction with   |
            |                         |                      CMEMS catalog products:       |
            |                         |                                                    |            
            | cmems_use_case          | Examples of how to download, read and display      |
            |                         | CMEMS data using NetCDF (Network Common Data Form) |
            |                         | files                                              |
            - ------------------------------------------------------------------------------
            
'/work/'   : Personnal folder that will persist through Jupyter Notebook sessions. 
             Store anything you want to keep in that folder.


- Installed packages:
Use 'pip list' shell command to list all installed packages & version.
Specific ones:

            - -------------------------------------------------------------------------------------------------------------
            | Package name            | Description                                        | www                          |
            - -------------------------------------------------------------------------------------------------------------
            | gdal                    | Geospatial Data Abstraction library                | https://www.gdal.org/        |  
            | matplotlib              | Python 2D plotting library                         | https://matplotlib.org/      | 
            | NumPy                   | Base N-dimensional array package                   | http://www.numpy.org/        |        
            | pandas                  | Python Data structures & analysis library          | https://pandas.pydata.org/   | 
            | s3cmd                   | Command line tool for managing Amazon S3           | https://s3tools.org/s3cmd    |       
            - -------------------------------------------------------------------------------------------------------------
            
To install additional package a notebook cell like this can be included:
! pip install <package_name>
The notebook environment also supports opening a terminal, in which this command can be executed as well. 


- Clipboard usage:
Dot   + Tab                  : completion in notebook
MAJ   + Insert               : paste text from clipboard
Shift + <right_mouse_button> : access to clipboard


- Webography:
Bounding box finder : http://bboxfinder.com
