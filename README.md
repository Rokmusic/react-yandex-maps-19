React Yandex Maps 19

React bindings for Yandex Maps API with experimental React 19 support. Fork

This repository is based on the original project:

    Original repository: https://github.com/R1ZEN/react-yandex-maps

    Original npm package: https://www.npmjs.com/package/@pbe/react-yandex-maps

    React 19 fork: https://github.com/Rokmusic/react-yandex-maps-19

The original source code and project structure are preserved as the basis of
this fork.

This fork contains experimental changes focused on React 19 compatibility and
testing. React 19

This fork uses:

    React 19.2.8

    React DOM 19.2.8

    React Test Renderer 19.2.8

The existing test suite has been successfully run with React 19. Installation

Install this React 19 fork directly from GitHub:

npm install git+https://github.com/Rokmusic/react-yandex-maps-19.git

The package name remains:

@pbe/react-yandex-maps

After installation, import the package normally:

import { YMaps, Map, Placemark } from '@pbe/react-yandex-maps';

Getting Started

import React from 'react'; import { YMaps, Map, Placemark } from
'@pbe/react-yandex-maps';

export default function App() { const defaultState = { center: [55.751574,
37.573856], zoom: 5, };

return ( <YMaps> <Map defaultState={defaultState}> <Placemark
geometry={[55.684758, 37.738521]} /> </Map> </YMaps> ); }

Development

Install dependencies:

npm install

Run tests:

npm test

Run TypeScript checks:

npm run typecheck

Build the package:

npm run build

Testing

The project currently uses React 19 and React Test Renderer 19.

Test command:

npm test

Current test suite:

    9 test suites

    75 tests

    React 19.2.8

Original Project

This project is based on:

https://github.com/R1ZEN/react-yandex-maps

Original package:

https://www.npmjs.com/package/@pbe/react-yandex-maps

Original documentation:

https://pbe-react-yandex-maps.vercel.app/ Documentation

    Getting Started: https://pbe-react-yandex-maps.vercel.app/

    Core Principles: https://pbe-react-yandex-maps.vercel.app/core-principles/

    API Reference: https://pbe-react-yandex-maps.vercel.app/category/api-reference/

License

MIT

This fork retains the MIT license of the original project.
