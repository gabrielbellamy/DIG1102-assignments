// Code taken from Animations.md in forked project "react-native" //

* `spring`: Simple single-spring physics model that matches [Origami](https://facebook.github.io/origami/).
 * `friction`: Controls "bounciness"/overshoot.  Default 7.
 * `tension`: Controls speed.  Default 40.
* `decay`: Starts with an initial velocity and gradually slows to a stop.
 * `velocity`: Initial velocity.  Required.
 * `deceleration`: Rate of decay.  Default 0.997.
 * 
 //String vales //

var App = React.createClass({
  componentWillMount() {
    // Animate creation
    LayoutAnimation.spring();
    
    var tweenState = require('react-tween-state');

var App = React.createClass({
  mixins: [tweenState.Mixin],
  
// Examples of Variables //

By default, if one animation is stopped or interrupted, then all other
animations in the group are also stopped.  Parallel has a `stopTogether` option
that can be set to `false` to disable this.

// example of a boolean //

  inputRange: [0, 1],
  outputRange: [0, 100],
  
  Which would map like so:

Input | Output
------|-------
  -400|    450
  -300|    300
  -200|    150
  -100|      0
   -50|    0.5
     0|      1
    50|    0.5
   100|      0
   101|      0
   200|      0
   
// Examples of arrays ...listing items in a container like manner //

getInitialState() {
    return { opacity: 1 }
  },
  
    return (
      <View style={{flex: 1, justifyContent: 'center', alignItems: 'center'}}>
        <TouchableWithoutFeedback onPress={this._animateOpacity}>
          <View ref={component => this._box = component}
                style={{width: 200, height: 200, backgroundColor: 'red',
                        opacity: this.getTweeningValue('opacity')}} />
                        
// examples of statements and declerations use of "return", "this", //

  
  