# MLOPS
Complete Automation of ML/DL model using Jenkins &amp; Docker

Most important thing to keep in mind is to change the names of the files after pull. 
* Dockerfile(ml) -> Dockerfile
* Dockerfile(dl) -> Dockerfile
### Keep the 2 files in 2 seperate folders and create the image.

* train(ml).py   -> train.py
* train(dl).py   -> train.py
### This is so because we will provide environment per code basis, so in one go only 1 file goes to the environment
