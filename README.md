
Developer Portfolio and Education
==========

A webpage used to exercise html, css and bootstrap. The portfolio will showcase accomplishments, demo techniques and evolve through feedback, exploration and creativity. It is in constant experimental condition to test error resolution and find improvement on standard practices. Currently displays a live-updated time-tracking chart, graphs and repository contributions.


[![Build status][shield-build]](#)

[![Dependencies][shield-dependencies]](#)


Table of Contents
-----------------

  * [Requirements](#requirements)
  * [Usage](#usage)
  * [Contributing](#contributing)
  * [Support](#support)
  * [License](#license)


Requirements
------------

Developer Portfolio and Education requires the following to run:

  * [Google Sheets][Sheets]
  * [githubchart-api][ghchart] (Thanks to 2016rshah)


Usage
-----

Replace all personal information in index.html then:

####For time tracking:

Create your google sheet then File>Publish to web

####Add it to index.html:

Replace link here with the google sheet link you generated.

```
<iframe class="chart" src="https://docs.google.com/spreadsheets/d/1oU8crZsV-PQ8OVBJOgB8eFLjMRRUi8z83Zr97FvRy4s/pubhtml?widget=true&amp;headers=false" style="border: 0">
      </iframe>
```
####Display repository

Follow instructions from [githubchart-api][ghchart]

replace this with your info

```
<img class = "chart2" src="http://ghchart.rshah.org/AlexanderNelson" alt="Alexander Nelson's Github chart" />
```


Contributing
------------

To contribute, clone this repo locally and commit your code on a separate branch. Please test and format before opening a pull-request:


Support
---------

Email: AmVetServ@gmail.com


License
-------

Copyright &copy; 2016, Alexander Nelson



[Sheets]: https://www.google.com/sheets/about/
[ghchart]: https://github.com/2016rshah/githubchart-api
[shield-dependencies]: https://img.shields.io/badge/dependencies-up%20to%20date-brightgreen.svg
[shield-build]: https://img.shields.io/badge/build-passing-brightgreen.svg