# React Series
Este pacote contém os arquivos básicos para iniciar as vídeo aulas
de React do [Canal V++](https://youtube.com/user/VPlusPlus).

# Jamess
- git clone ...
- npm install
- sudo npm install -g webpack


src/app.js
------

import React     from 'react';
import ReactDOM from 'react-dom';

import App from './components/App';

ReactDOM.render(
	<App />,
	document.getElementById("app")
);


src/components/App.js
------

import React from 'react';

export default class App extends React.Component {
	render() {
		return <h1>Olá React tatata</h1>;
	}
}

ERROR in Cannot find module 'babel-core'
------
npm install babel-core babel-loader --save-dev
