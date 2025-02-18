# pattern_generator
PDF pattern generator of AprilTags and AR tags
## Dependencies
* [*PyFPDF*](https://pyfpdf.readthedocs.io/en/latest/index.html)  a library for PDF document generation under Python
* [*PyYAML*](https://pyyaml.org/)  a full-featured YAML framework for the Python
```
sudo pip3 install fpdf pyyaml
```
## Usage
* Configuration file [**cfg.yaml**](https://github.com/cgdsss/pattern_generator/blob/master/cfg.yaml)
* Run scripts
  ```
  python3 tag.py
  ```
* A pdf file was generated, like [pattern.pdf](https://github.com/cgdsss/pattern_generator/blob/master/pattern.pdf)
## Resources
Here are some related links:
* [AprilTag's home](https://april.eecs.umich.edu/software/apriltag/) 
* [ROS AR_tag Detection](http://wiki.ros.org/ar_track_alvar)
* [ROS AprilTag Detection](http://wiki.ros.org/apriltags2_ros)
