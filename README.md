# Deep-Learning-Computation

## Layers and Blocks
<li> take a set of inputs 
<li> generatecorresponding outputs, and 
<li> are described by a set of tunable parameters.

### <ol> A Custom Block
### <ol> The Sequential Block
  <li> A function to append blocks one by one to a list.
  <li> A forward propagation function to pass an input through the chain of blocks, in the same order as they were
      appended

### <ol> Executing Code in the Forward Propagation Function


## Parameter Management
• Accessing parameters for debugging, diagnostics, and visualizations. <br>
• Parameter initialization.<br>
• Sharing parameters across different model components.<br>

## Deferred Initialization
• We defined the network architectures without specifying the input dimensionality. <br>
• We added layers without specifying the output dimension of the previous layer. <br>
• We even “initialized” these parameters before providing enough information to determine how many parameters our models should contain.
    
    
  
