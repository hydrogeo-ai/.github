GeoTracker
----------
Owns:
- Frame
- Detection
- SegmentationResult
- Detector
- Segmenter
- Tracker
- Geolocator
- PerceptionPipeline
- inference backends

Does NOT own:
- ROS2
- FastAPI
- databases
- drone control
- dashboards

GeoTracker-edge
--------
Owns:
- ROS2
- camera integration
- GPS / IMU adapters
- edge runtime
- robot/drone process

GeoTracker-platform
------------
Owns:
- API
- persistence
- surveys
- observations
- map/dashboard
