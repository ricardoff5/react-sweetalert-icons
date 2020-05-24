# Animated SweetAlert Icons for React
A clean and simple React wrapper for [SweetAlert](https://sweetalert.js.org/)'s fantastic status icons. This wrapper is intended for users who are interested in _just_ the icons. For the standard SweetAlert modal with all of its bells and whistles, you should probably use [React-Bootstrap-SweetAlert](https://github.com/djorg83/react-bootstrap-sweetalert)

<p align="center">
    <img src="https://gyazo.com/a045a1b5c96860c6e75ed0c7e48a3c81/raw" alt="Example usage">
</p>

## Install
```bash
npm install --save react-sweetalert-icons
```

## Import
```js
import SweetIcons from 'react-sweetalert-icons';

```

## Use
```react
    <!-- Type can be one of: "success", "warning", "info", "error" and "loading" -->
    <SweetIcons type="success" />
```
## Resizing

Resizing have been a real problem using this icons what was made of full CSS. Effects params wasn't done in a proportion from size. So i use an workaround of local zoom to change its size.

```react
    <!-- Zoom can any double value with 1 case: 0.1, 0.2 ..., 4.9, 5.0 -->
    <SweetIcons type="success" zoom={0.7}/>
```

## Credits
- [SweetAlert](https://sweetalert.js.org/)
- [Alexandre Chopin](https://codepen.io/alexchopin/)
- [Jorgen Vatle](https://github.com/JorgenVatle)

## License
ISC
