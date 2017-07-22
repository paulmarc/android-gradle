android-gradle
==============
Gradle Scripts useful to me and hopefully you.

# Versioning
* **File**: versions.gradle
* **Purpose**: Auto-increment builds.
  * reset increment on version change (Major, Minor, Patch);
  * APK generated with version code appended.
* **Usage**:
  * Add the code in versions.gradle to your build.gradle;
  * Create 'version.properties' file, with the following:  
```bash
VERSION_MINOR=0
VERSION_PATCH=0
VERSION_CODE=100
VERSION_MAJOR=1
```
  * Build and generate your APK!  
Everytime you change any of the Major, Minor or Patch values, VERSION_CODE will reset.
