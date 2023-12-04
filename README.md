# Reactapp
create a folder on desktop
open folder open cmd 
create-react-app myapp
npm start
open vs code
open index.js
open terminal enter npm start
change the code according to u
This is 2 React app programs
odd even
import React from 'react';
import ReactDOM from 'react-dom/client';
import './index.css';
import App from './App';
import reportWebVitals from './reportWebVitals';
const a=8
let m="odd"
if(a%2==0)
{
  m="even"
}

const root = ReactDOM.createRoot(document.getElementById('root'));
root.render(
  <h1><b><center>{m}</center></b></h1>
);

// If you want to start measuring performance in your app, pass a function
// to log results (for example: reportWebVitals(console.log))
// or send to an analytics endpoint. Learn more: https://bit.ly/CRA-vitals
reportWebVitals();

This is 3 program underlist
import React from 'react';
import ReactDOM from 'react-dom/client';
import './index.css';
import App from './App';
import reportWebVitals from './reportWebVitals';
const car = <h3>
  <ul>
    <li>Ford</li>
    <li>Audi</li>
    <li>TATA</li>
    <li>BMW</li>
  </ul>
 
</h3>

const root = ReactDOM.createRoot(document.getElementById('root'));
root.render(
  <h1><b><center>{car}</center></b></h1>
);

// If you want to start measuring performance in your app, pass a function
// to log results (for example: reportWebVitals(console.log))
// or send to an analytics endpoint. Learn more: https://bit.ly/CRA-vitals
reportWebVitals();


