# OrbitControls to React
OrbitControls.js converted to ES6(https://lebab.io/) and ready to use with plain Three.js with React

Plain Three.js:https://github.com/Carnaux/react-electron-parcel-three


# How to use

#### Just add 

```
import "../wherever you put it/OrbitControls";
```

#### in the file that you used Three.js

#### ...

```
const controls = new THREE.OrbitControls(camera);

this.controls = controls;
```
#### ...

```
 animate(){ 
 
    this.controls.update
    
 }
```