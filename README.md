# README

en este proyecto quiero aplicar CSS puro html + javascript
en el css quiero usar sus nuevas caracteristicas ya que solo conozco de bootstrap y materialize.

# css a considerar

- bem
- sass
- selectores
- multicolumn 
- css grid layout 
- flexbox 
- styled component

# organizar styled component
https://stackoverflow.com/questions/42987939/styled-components-organization

-src/    
 -app.js
 -app/  
 ---libs  
 ---modelo  
 ---imagenes  
 ---pages  
 ---componentesglobales    //shared
 ---componentes secciones  

pued agrgar a cada carpeta su styled.js o mejorar crear componente styled completo
src
├── app.js  
├── Routes
├── Context
├── Hooks
├── Layout
│   │
│   ├── Header
│   │   ├── Logo.jsx    
│   │   ├── styled.js
│   │   ├── container.js
│   │   └── index.js
│   └── LeftPanel
│       ├── LeftPanel.jsx
│       ├── styled.js
│       └── index.js
├── Components
│      ├────buttons
│      │       ├── buttonAccept.js
│      │       └── buttonCancel.js
│      ├────text
│      │       ├── title.js
│      │       └── subtitle.js
│      ├────inputs
│      │       ├── inputlong.js
│      │       └── inputsmall.js
│      ├────carousel
│      │       ├── carouseltop.js
│      │       └── carouselbot.js
│      └────map
│              ├── mapExample.js
│              └── mapRealTime.js

