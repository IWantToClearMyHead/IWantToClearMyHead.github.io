```json
   // code for coloring
```
```html
   // code for coloring
```
```js
   // code for coloring
```
```css
   // code for coloring
```
// etc.

```js
  import { Component } from '@angular/core';
  import { MovieService } from './services/movie.service';

  @Component({
    selector: 'app-root',
    templateUrl: './app.component.html',
    styleUrls: ['./app.component.css'],
    providers: [ MovieService ]
  })
  export class AppComponent {
    title = 'app works!';
  }
```
