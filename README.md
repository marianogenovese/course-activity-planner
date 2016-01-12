This project is affiliated with the [Maison du logiciel libre (ML<sup>2</sup>)](https://maisonlogiciellibre.org/) at <img src="http://www.etsmtl.ca/ETS/media/Prive/logo/ETS-rouge-ecran-fond_transparent.png" alt="ETS" width="64">.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [course-activity-planner](#course-activity-planner)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# course-activity-planner
Tool for instructors to plan course activities and synchronize the data with syllabus, LMS, etc.

### Setup
* Setup a python virtualenv
```
cd python && virtualenv-3.4 env
```

### Run unit tests
* Activate the python virtualenv
```
. env/bin/activate
```
* Install the dependencies
```
pip install -r requirements.txt
```
* Run the test suite
```
nosetests
```
* Optionally, you can get a coverage report
```
nosetests --with-coverage
```
