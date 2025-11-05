To get the Group Link Network lib on your project. Follow the steps below:

Add it in your root settings.gradle at the end of repositories:
```groovy
	dependencyResolutionManagement {
		...
		repositories {
			mavenCentral()
			maven { url 'https://www.jitpack.io' }
		}
	}
```
> Add the jitpack repository to other configurations as needed

Step 2. Add the dependency
```
	dependencies {
	        implementation 'com.grouplinknetwork:lib-grouplinknetwork:4+'
	}   
```

For more information:
https://docs.grouplinknetwork.com/docs/SDK%20Documentation/Introduction/
