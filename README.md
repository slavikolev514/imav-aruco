# imav-aruco
IMAV aruco detection
## build:
g++ src/detect_markers.cpp -o main `pkg-config --cflags --libs opencv4`

## run aruco example with dict - see keys object for number to dict correspondences (7=DICT_5X5_1000):
./main -d=7 -r -c=src/tutorial_camera_params.yml