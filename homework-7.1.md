 // This code is taken from forked project REACT-NATIVE the folder its under is NAVIGATOR and the file name is BREADCRUMBNAVsample
 // LINK   https://github.com/gabrielbellamy/react-native/blob/master/Examples/UIExplorer/Navigator/BreadcrumbNavSample.js 
 

      rightContentForRoute: function(route, navigator) {
        return null;
      },
      
// This funtion appears to be called Right Content for Route its arguments are ROUTE & NAVIGATOR 

// The scope variable is "return" ***Return is a command to return from the function, it is not a variable.

// the RETURN Value is NULL 
      
      titleContentForRoute: function(route, navigator) {
        return (
          <TouchableOpacity
            onPress={() => navigator.push(_getRandomRoute())}>
            <Text style={styles.titleText}>{route.title}</Text>
          </TouchableOpacity>
        );
      },
      
// This funtion appears to be called Title Content for Route its arguments are ROUTE & NAVIGATOR 

// The scope variable is "return" ***Return is a command to return from the function, it is not a variable.

// the RETURN Value is TouchableOpacity which should give you Navigator.push,       
      
      iconForRoute: function(route, navigator) {
        return (
          <TouchableOpacity
            onPress={() => { navigator.popToRoute(route); }}
            style={styles.crumbIconPlaceholder}
          />
        );
      },
 
// This funtion appears to be called Icon for Route its arguments are ROUTE & NAVIGATOR 

// The scope variable is "return"  ***Return is a command to return from the function, it is not a variable.

// the RETURN TouchableOpacity which should give you { navigator.popToRoute(route); }} onPress
      
      
      separatorForRoute: function(route, navigator) {
        return (
          <TouchableOpacity
            onPress={navigator.pop}
            style={styles.crumbSeparatorPlaceholder}
          />
        );
      }
    };
  },
  
  
  // This funtion appears to be called Separator for Route its arguments are ROUTE & NAVIGATOR 

// The scope variable is "return"  ***Return is a command to return from the function, it is not a variable.

// the RETURN Value is TouchableOpacity which should give {navigator.pop} on press and style which should give  {styles.crumbSeparatorPlaceholder}
