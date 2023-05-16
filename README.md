# Scratch-GUI-3.0
Created new block operator and added some functionality

- operators.js => Created 'Square' and ‘Square Root’ block inside scratch-blocks/blocks_vertical/operators.js
- scratch3_operators.js => Created logic of square inside a new function at scratch-vm/src/blocks/scratch3_operators.js

1. cloned the repo as shown
```
git clone https://github.com/scratchfoundation/scratch-gui.git
```
```
git clone https://github.com/scratchfoundation/scratch-blocks.git
```
```
git clone https://github.com/scratchfoundation/scratch-vm.git
```

2. Installed the dependencies 
```
npm install
```

3. Linked the scratch-gui with scratch-vm and scratch-blocks as discussed [here](https://github.com/scratchfoundation/scratch-gui/wiki/Getting-Started)

4. 'Square' & 'Square Root' block has been created in ```operator.js``` file(location: ```scratch-blocks/blocks_vertical/operators.js```)

5. Added the functionality for those blocks in ```scratch3_operators.js``` file(location: ```scratch-vm/src/blocks/scratch3_operators.js```)

