if [ -z "$1" ]
  then
    echo "You must supply an OS version as the first arg, e.g. 8.1"
    exit 255
fi
<CONDITIONS> If and then

 "name": "react-native",
  "version": "0.8.0",
  "description": "A framework for building native apps using React",
  "license": "BSD-3-Clause",
  "repository": {
    "type": "git",
    "url": "git@github.com:facebook/react-native.git"
<STRING VALUES> a string of values

<TouchableOpacity accessible={true} accessibilityLabel={'Tap me!'} onPress={this._onPress}>
  <View style={styles.button}>
<BOOLEAN> example of testing true statement

_onPress: function() {
  this.state.radioButton = this.state.radioButton === “radiobutton_checked” ?
  “radiobutton_unchecked” : “radiobutton_checked”;
  if (this.state.radioButton === “radiobutton_checked”) {
    RCTUIManager.sendAccessibilityEvent(
      React.findNodeHandle(this),
      RCTUIManager.AccessibilityEventTypes.typeViewClicked);
<FUNCTION> telling a button what to do 

<View style={styles.container}>
  <View style={{position: 'absolute', left: 10, top: 10, right: 10, height: 100,
    backgroundColor: 'green'}} importantForAccessibility=”yes”>
    <Text> First layout </Text>
    
<ARRAY> a list of values within a varaiable LEFT TOP RIGHT HEIGHT 
