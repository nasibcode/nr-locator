# nr-locator
Static library repository for get location update.

# How to use this library?

1. Clone or download the project.
2. Drag or copy/paste all Static Library Files folder content in your project.
3. If your project in swift then you need to create a bridge-header and include all header file in that header file. 
4. But If you are using this library in objective c project then you just need to include header file where you want your current location.
5. For getting location on terminate/background state you need to enable background mode-> location update or just add these line you .plist file.
  <key>UIBackgroundModes</key>
	<array>
		<string>location</string>
	</array>
  
6. Add this line in you info.plist file.

  <key>NSLocationAlwaysUsageDescription</key>
	<string>Need location manager permission for getting user current location.</string>
