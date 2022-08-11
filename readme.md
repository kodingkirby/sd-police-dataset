## run with docker
docker run -it --rm -p 8888:8888 -v C:\Users\user\Desktop\sd-police-dataset:/home/jovyan/work jupyter/datascience-notebook:latest

## run with python
python3 -m venv sd-crime
.\sd-crime\Scripts\activate
pip install pandas matplotlib IPython


pip install pipwin
pipwin install gdal
pipwin install fiona
pip install geopandas mapclassify adjustText folium