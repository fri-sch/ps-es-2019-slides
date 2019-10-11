# Interactive Slides for "2. Esslinger Preacher Slam"

This project uses the [reveal.js HTML presentation framework](https://github.com/hakimel/reveal.js)
and [slam.js](https://github.com/fri-sch/slam.js) to provide interactive slides
for a poetry slam, that takes place in Esslingen, Germany in 2019.

The contestants present their contributions on stage and get rated by the
audience. As the ratings are presented, they are entered into the control
interface and shown to the audience.

## Usage

1. Clone the repository.

       git clone https://github.com/fri-sch/ps-es-2019-slides.git
       cd ps-es-2019-slides

2. Install the dependencies.

       npm install

3. Run the server.

       node node_modules/slam.js

   You should see something like the following. Follow the instructions.

       slam.js - Kleinkunst Competition Interactive Slides
       1. Open the slides at http://localhost:1947
       2. The control page should open automatically in a separate window.
          If not, click on the link in your JS console
       3. Enter your competition data live and go through the slides as needed

## License

Licensed under the MIT license, see LICENSE file.

Copyright (C) 2019 Frieder Schrempf
