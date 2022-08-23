# Meta-data-Extractor-of-Images
This python script extract the basic information of the images.

## Get meta information of images


### Note
- Install requirememtns.txt before running the script.

- Make sure the picture contains location information, otherwise the location cannot be obtained<br>
you need fill in your email address to use the function in ```gps_utils.py```: 
```python
geolocator = Nominatim(user_agent = "your email")
```

### Usage
```python get_meta_from_pic.py image_file```
