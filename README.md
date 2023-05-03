## Dynamic Response of Shear Buildings Using ML (DRSB-ML)

A web application for rapid predictions of the dynamic response of multi-story buildings, using optimized ML models based on gradient boosting on decision trees with categorical features support (CatBoost) alorithm. More specific the application is able to predict the fundamental eigenperiod (T<sub>1</sub>), the horizontal displacement at the top story (U<sub>top</sub>) and the normalized shear base over the mass of each story (V<sub>b</sub>) of a shear building (see figure below).

![Shear Building Model](static/shear_building_model.png)

### Installation and Requirements
-----------------------------
First you need to create a new virtual environment based on Python version 3.9. After activating the new enviroment run the following command to install the required packages:

    pip install -r requirements

To use the application run the following:

    flask run

Visit http://localhost:5000 or http://127.0.0.1:5000 in your favorite browser to see the application running:

![Web App Live](static/web_application_gui.png)

License
-------
DRSB-ML is released under the MIT license.

Author
------
Manolis Georgioudakis (geoem@mail.ntua.gr)

Copyright © 2023