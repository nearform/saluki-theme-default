<h1 align="center">saluki-theme-default</h1>

Saluki's default theme contains a robust suite of configurable rules to get you started.

Take a look at [Saluki's quick start guide](https://github.com/nearform/saluki#usage) for details on how to use, configure and extend this theme.

## Rules

<table>
  <tr>
    <th align='left'>Rule</th>
    <th align='left'>Defaults</th>
  </tr>
  <tr>
    <td>color</td>
    <td><pre><code>{
  black: 'black',
  white: 'white',
  lighterGray: '#d5d9dc',
  lightGray: '#9ea6ae',
  gray: '#495057',
  darkGray: '#3a4045',
  darkerGray: '#23262a',
  lighterRed: '#f9b8b8',
  lightRed: '#f25959',
  red: '#f03e3e',
  darkRed: '#a60d0d',
  darkerRed: '#470606',
  lighterBlue: '#bbdaf6',
  lightBlue: '#61a9ea',
  blue: '#1c7ed6',
  darkBlue: '#155d9e',
  darkerBlue: '#092844',
  lighterYellow: '#ffe4b3',
  lightYellow: '#ffc04d',
  yellow: '#f59f00',
  darkYellow: '#b37400',
  darkerYellow: '#4d3200',
  lighterGreen: '#c5edcc',
  lightGreen: '#77d587',
  green: '#37b24d',
  darkGreen: '#2a883b',
  darkerGreen: '#123a19',
  lighterOrange: '#fdd2b5',
  lightOrange: '#fa9551',
  orange: '#f76707',
  darkOrange: '#ae4805',
  darkerOrange: '#4a1f02',
  lighterPurple: '#e6c3ee',
  lightPurple: '#c474d8',
  purple: '#ae3ec9',
  darkPurple: '#78278b',
  darkerPurple: '#33113c'
}</code></pre></td>
  </tr>
  <tr>
    <td>backgroundColor</td>
    <td>Inherited from color</td>
  </tr>
  <tr>
    <td>borderColor</td>
    <td>Inherited from color</td>
  </tr>
  <tr>
    <td>breakpoint</td>
    <td><pre><code>{
  notSmall: { min: '576px' },
  medium: { min: '768px', max: '991px' },
  large: { min: '992px' }
}</code></pre></td>
  </tr>
  <tr>
    <td>padding</td>
    <td><pre><code>{
  none: '0',
  auto: 'auto',
  small: '1rem',
  medium: '2rem',
  large: '4rem'
}</code></pre></td>
  </tr>
  <tr>
    <td>paddingVertical</td>
    <td>Inherited from padding</td>
  </tr>
  <tr>
    <td>paddingHorizontal</td>
    <td>Inherited from padding</td>
  </tr>
  <tr>
    <td>paddingTop</td>
    <td>Inherited from padding</td>
  </tr>
  <tr>
    <td>paddingRight</td>
    <td>Inherited from padding</td>
  </tr>
  <tr>
    <td>paddingBottom</td>
    <td>Inherited from padding</td>
  </tr>
  <tr>
    <td>paddingLeft</td>
    <td>Inherited from padding</td>
  </tr>
  <tr>
    <td>margin</td>
    <td><pre><code>{
  none: '0',
  auto: 'auto',
  small: '1rem',
  medium: '2rem',
  large: '4rem'
}</code></pre></td>
  </tr>
  <tr>
    <td>marginVertical</td>
    <td>Inherited from margin</td>
  </tr>
  <tr>
    <td>marginHorizontal</td>
    <td>Inherited from margin</td>
  </tr>
  <tr>
    <td>marginTop</td>
    <td>Inherited from margin</td>
  </tr>
  <tr>
    <td>marginRight</td>
    <td>Inherited from margin</td>
  </tr>
  <tr>
    <td>marginBottom</td>
    <td>Inherited from margin</td>
  </tr>
  <tr>
    <td>marginLeft</td>
    <td>Inherited from margin</td>
  </tr>
  <tr>
    <td>fontSize</td>
    <td><pre><code>{
  small: '1rem',
  medium: '1.25rem',
  large: '2.5rem'
}</code></pre></td>
  </tr>
    <tr>
    <td>fontFamily</td>
    <td><pre><code>{
  sans:
    '-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial,
    Noto Sans, sans-serif, Apple Color Emoji, Segoe UI Emoji, Segoe UI Symbol,
    Noto Color Emoji',
  serif: 'Georgia, Times, Times New Roman, serif'
}</code></pre></td>
  </tr>
    <tr>
    <td>fontWeight</td>
    <td><pre><code>{
  thin: '200',
  normal: 'normal',
  bold: '700'
}</code></pre></td>
  </tr>
  <tr>
    <td>lineHeight</td>
    <td><pre><code>{
  none: '1',
  small: '1.25',
  medium: '1.5',
  large: '2'
}</code></pre></td>
  </tr>
  <tr>
    <td>letterSpacing</td>
    <td><pre><code>{
  small: '-.05em',
  none: '0',
  medium: '.025em',
  large: '.05em'
}</code></pre></td>
  </tr>
  <tr>
    <td>width</td>
    <td><pre><code>{
  fifth: '20%',
  twoFifths: '40%',
  threeFifths: '60%',
  fourFifths: '80%',
  quarter: '25%',
  threeQuarters: '75%',
  third: '33.3333333333%',
  twoThirds: '66.6666666666%',
  half: '50%',
  full: '100%',
  view: '100vw',
  auto: 'auto'
}</code></pre></td>
  </tr>
  <tr>
    <td>minWidth</td>
    <td>Inherited from width</td>
  </tr>
  <tr>
    <td>maxWidth</td>
    <td>Inherited from width</td>
  </tr>
  <tr>
    <td>height</td>
    <td><pre><code>{
  small: '2rem',
  medium: '4rem',
  large: '8rem',
  quarter: '25%',
  half: '50%',
  threeQuarters: '75%',
  full: '100%',
  view: '100vh',
  auto: 'auto'
}</code></pre></td>
  </tr>
  <tr>
    <td>minHeight</td>
    <td>Inherited from height</td>
  </tr>
  <tr>
    <td>maxHeight</td>
    <td>Inherited from height</td>
  </tr>
  <tr>
    <td>borderWidth</td>
    <td><pre><code>{
  none: 'none',
  thin: '1px',
  medium: '2px',
  thick: '4px',
  extraThick: '8px'
}</code></pre></td>
  </tr>
  <tr>
    <td>borderRadius</td>
    <td><pre><code>{
  none: 0,
  small: '.125rem',
  medium: '.25rem',
  large: '.5rem',
  round: '9999px'
}</code></pre></td>
  </tr>
  <tr>
    <td>opacity</td>
    <td><pre><code>{
  full: 1,
  half: 0.5,
  none: 0,
  inherit: 'inherit'
}</code></pre></td>
  </tr>
  <tr>
    <td>boxShadow</td>
    <td><pre><code>{
  small: '0 1px 3px rgba(0,0,0,0.12), 0 1px 2px rgba(0,0,0,0.24)',
  medium: '0 3px 6px rgba(0,0,0,0.16), 0 3px 6px rgba(0,0,0,0.23)',
  large: '0 14px 28px rgba(0,0,0,0.25), 0 10px 10px rgba(0,0,0,0.22)'
}</code></pre></td>
  </tr>
</table>

## License

Copyright 2019 NearForm

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
