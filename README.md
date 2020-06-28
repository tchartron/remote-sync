## Remote folder synchronization
  
Watch folder and rsync changes to a remote host.  
Usefull if you're using a remote host to serve your app such as a remote machine running a docker container during development.  
__Note :__ the _osascript_ and _fswatch_ are specific to MacOS to display a notification, and watch filesystem, you can use _inotifywait_ and remove the notification part on Linux  
