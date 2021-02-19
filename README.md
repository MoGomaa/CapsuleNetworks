# CapsuleNetworks
This is Tensorflow 2 implementation for DigitCaps Capsule Networks using custom Layers and Models subclassing methon

## Requirements

The model contains the following libraries and frameworks
- Tensorflow 2.4

## Useful Links:
- Paper- "Dynamic Routing Between Capsules": [Link](https://papers.nips.cc/paper/2017/file/2cad8fa47bbef282badbb8de5374b894-Paper.pdf)
- Blog Tutorial - "Implementing Capsule Network in TensorFlow": [Link](https://radiant-brushlands-42789.herokuapp.com/towardsdatascience.com/implementing-capsule-network-in-tensorflow-11e4cca5ecae)
- GitHub reference: [Link](https://github.com/dedhiaparth98/capsule-network)

**Note:** <br />The implementation is quite different<br />I treated the Capsule Layer as if it's a Fully Connected Layer but instead of that each neuron has scalar value it's treated as a vector<br />
- The "CapsPrimary" Layer just reshapes the input tensor to the required shape (num_capsules, capsule_dimension) 
- The "CapsFC" do the actual routing

![DigitCaps](https://github.com/MoGomaa/CapsuleNetworks/blob/main/CapsuleNetwork.png)
