THIS CODE WAS TAKEN FROM Accessibility.MD in REACTIVE-NATIVE in folder "DOCS"


if [ -z "$1" ] then echo "You must supply an OS version as the first arg, e.g. 8.1" exit 255 fi 

// CONDITIONS If and then //

"name": "react-native", "version": "0.8.0", "description": "A framework for building native apps using React", 
"license": "BSD-3-Clause", "repository": { "type": "git", "url": "git@github.com:facebook/react-native.git" 

// STRING VALUES a string of values //


When `true`, indicates that the view is an accessibility element. When a view is an accessibility element, it groups its children into a single selectable component. By default, all touchable elements are accessible.
On Android, ‘accessible={true}’ property for a react-native View will be translated into native ‘focusable={true}’.
```javascript
<View accessible={true}>
  <Text>text one</Text>
  <Text >text two</Text>
</View>

// BOOLEAN example of testing true statement //

_onPress: function() { this.state.radioButton = this.state.radioButton === “radiobutton_checked” ? “radiobutton_unchecked” : “radiobutton_checked”; if (this.state.radioButton === “radiobutton_checked”) 
{ RCTUIManager.sendAccessibilityEvent( React.findNodeHandle(this), RCTUIManager.AccessibilityEventTypes.typeViewClicked);

// FUNCTIONS telling a button what to do //

Which would map like so:

Input	Output
-400	450
-300	300
-200	150
-100	0
-50	0.5
0	1
50	0.5
100	0
101	0
200	0

// Arrays ...listing items in a container like manner //

getInitialState() { return { opacity: 1 } },

return (
  <View style={{flex: 1, justifyContent: 'center', alignItems: 'center'}}>
    <TouchableWithoutFeedback onPress={this._animateOpacity}>
      <View ref={component => this._box = component}
            style={{width: 200, height: 200, backgroundColor: 'red',
                    opacity: this.getTweeningValue('opacity')}} />

// examples of statements and declerations use of "return", "this", //


THE CODE BELOW COMES FROM NativeComponentsAndroid in DOCS folder

In this example we create view manager class `ReactImageManager` that extends `SimpleViewManager` of type `ReactImageView`. `ReactImageView` 
is the type of object managed by the manager, this will be the custom native view. Name returned by `getName` is used to reference the native view type from JavaScript.

// Stings and STRING METHODS words or phrases caprtured in parentheses or commmas //

THE CODE BELOW IS LOCATED IN FOLDER Game2048.js

  var direction = -1;
    if (Math.abs(deltaX) > 3 * Math.abs(deltaY) && Math.abs(deltaX) > 30) {
      direction = deltaX > 0 ? 2 : 0;
    } else if (Math.abs(deltaY) > 3 * Math.abs(deltaX) && Math.abs(deltaY) > 30) {
      direction = deltaY > 0 ? 3 : 1;

// Math Objects  and Comparison Operators // 

//NO NUMBERS OR NUMBER STTEMENTS could be found//
