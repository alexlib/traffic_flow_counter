# Traffic flow counter :vertical_traffic_light:

## Introduction
Hello everyone! The following code will be a current work-in-progress app for traffic flow counting. My hope is to make this something of value for my city to be used for traffic flow management.This uses the `yolo-v3` computer vision model to vehicles.

## Setup
To run the app locally, install the necessary python packages by: 

```python
pip install requirements.txt
```
For better reproducibility, make sure open up a python environment using `virtualenv` or any of your favorite python environment packages. 

The app contains a custom slider. To use it, make sure you have `npm` installed and then run the following commands.
```sh
cd components/custom_slider/frontend/
npm run build
```
This should recreate the build package for the custom slider. 

Afterwards run the app!
```
streamlit run app app/streamlit-app.py
```

## Future Developments
Here are some of my ideas that would be neat additions to the API: 
+ Speed measurement
+ Vehicle distribution measurement
+ Traffic density


