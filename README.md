# OpenAssistant WebVR

A WebVR space for the open source [OpenAssistant](http://openassistant.org/) AI project.

See a [demo](http://michaelgaio.com/vr/openassistant/)!

Use: W A S D keys to move around in space.  Space bar is jump!

[![OA-VR-0.0.11.png](https://s3.postimg.org/v3n3q4t3n/OA_VR_0_0_11.png)](https://postimg.org/image/k41wej2of/)

[![OA-VR-0.0.115.png](https://s17.postimg.org/d3y5xs5db/OA_VR_0_0_115.png)](https://postimg.org/image/d3y5xs5d7/)

## Getting Started

To run locally, simply just open the index.html in a WebVR enabled web browser.

To develop locally, it's recommended to utilize Node.js for live updating (see Local Development below).

To run remotely, just upload index.html, images, shaders, and components onto any standard web server.  

### Installing

First make sure you have [Node.js](https://nodejs.org/en/download/package-manager/) installed.

Then inside the project directory, install the Node dependencies:

    npm install

### Local Development

To serve from a simple Node development server:

    npm start

Will automatically launch into the browser and do live updating when changes are made:

[__http://localhost:3000/__](http://localhost:3000/)

## Authors

* [Michael Gaio](http://www.michaelgaio.com) - [miquael](https://github.com/miquael) - *Initial work*

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Built With

* [A-Frame](https://aframe.io/) - an awesome WebVR framework.

## Acknowledgments

* See [Vavrek's](https://github.com/vavrek) open source [OpenAssistant GitHub](https://github.com/vavrek/openassistant)
* Thanks to [ngokevin](https://github.com/ngokevin) for his [kframe](https://github.com/ngokevin/kframe)
* Thanks to [donmccurdy](https://github.com/donmccurdy) for his [aframe-extras](https://github.com/donmccurdy/aframe-extras)
