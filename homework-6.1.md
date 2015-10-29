

Code pulled from react-native FOLDER EXAMPLES and GAME BOARD JS file

Tile.prototype.isNew = function () {
  return this.oldRow === -1 && !this.mergedInto;
 // prototype is new perform function show old intro then make merge into new intro // 
 
 
  Tile.prototype.fromRow = function () {
  return this.mergedInto ? this.row : this.oldRow;
};
// take prototype is certain row and perform function merges rows into a merged intro //


Tile.prototype.fromColumn = function () {
  return this.mergedInto ? this.column : this.oldColumn;
};
// take prototype from column that is a certain function //


Tile.prototype.toRow = function () {
  return this.mergedInto ? this.mergedInto.row : this.row;
};
// perform prototype toRow function then return to merge intro //


Tile.prototype.toColumn = function () {
  return this.mergedInto ? this.mergedInto.column : this.column;
};
// perform prototype to Column then perform fuction merged intro //


The following code pulled from react-native WEBSITE FOLDER and GrandLew File 

while [ -h "$PRG" ] ; do
    ls=`ls -ld "$PRG"`
    link=`expr "$ls" : '.*-> \(.*\)$'`
    if expr "$link" : '/.*' > /dev/null; then
        PRG="$link"
 else
        PRG=`dirname "$PRG"`"/$link"       
       
if [ -n "$JAVA_HOME" ] ; then
    if [ -x "$JAVA_HOME/jre/sh/java" ] ; then
        # IBM's JDK on AIX uses strange locations for the executables
        JAVACMD="$JAVA_HOME/jre/sh/java"
    else
        JAVACMD="$JAVA_HOME/bin/java"
    fi
    if [ ! -x "$JAVACMD" ] ; then
        die "ERROR: JAVA_HOME is set to an invalid directory: $JAVA_HOME
// While performing -H DO other things to Determine the Java commands listed. //  


if [ "$cygwin" = "false" -a "$darwin" = "false" ] ; then
    MAX_FD_LIMIT=`ulimit -H -n`
    if [ $? -eq 0 ] ; then
        if [ "$MAX_FD" = "maximum" -o "$MAX_FD" = "max" ] ; then
            MAX_FD="$MAX_FD_LIMIT"
        fi
        ulimit -n $MAX_FD
        if [ $? -ne 0 ] ; then
            warn "Could not set maximum file descriptor limit: $MAX_FD"
        fi
    else
        warn "Could not query maximum file descriptor limit: $MAX_FD_LIMIT"
//  If cygwin is false then perform MAX FD LIMIT. Increase the maximum file descriptors if maximum file is not reached //
        