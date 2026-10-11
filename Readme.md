# Parking Places Counter

Count free parking spaces in fixed-camera video using OpenCV image processing. Based on Murtaza Hassan's tutorial.

```sh
pip install -r requirements.txt
python main.py
```

The demo loops `carPark.mp4` and displays the count in an OpenCV window. For your own footage, mark spaces with `ParkingSpacePicker.py` and adjust the rectangle size and pixel threshold in `main.py`. The supplied positions and threshold are specific to the sample camera.
