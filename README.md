# BBC-Technical-Assessment
BBC-Technical-Assessment to automate 7 test scenarios based for Android 

# Test Technical Assessments for Android 

This repository contains automated test scripts for 7 scenarios as part of test technical assessment for Android device. 

## Requirements
### Android
- **Android Studio**: Version Ladybug or later  
- **Android SDK**: API Level 26 or higher (running on the device only)  
# Native UI Test for Android Application using JetPack Compose Framework 
In this project, the JetPack Compose framework used to write test scripts using  Java/Kotlin.

## Installation

### Pre-requisites
•⁠  ⁠Java SDK

•⁠  ⁠Gradle

•⁠  ⁠Android Studio 

-Configure below the Java, SDK & Android home paths in .zshrc or .bash_profile file as applicable
export "JAVA_HOME=\$(/usr/libexec/java_home)" >> ~/.zshrc
export ANDROID_HOME=$HOME/Library/Android/sdk
export PATH=$PATH:$ANDROID_HOME/emulator
export PATH=$PATH:$ANDROID_HOME/tools
export PATH=$PATH:$ANDROID_HOME/tools/bin
export PATH=$PATH:$ANDROID_HOME/platform-tools


###dependencies

•⁠  ⁠Install all the necessary  dependencies  defined in the gradle.properties file


## How to run tests 

1.⁠ ⁠Clone or download this repository(https://github.com/test-technical-assessments-RamyaM.zip)

2. Decompress the file test-technical-assessments-RamyaM.zip

3.⁠ ⁠Install all the dependencies as per pre-requisites

4. Automated scripts for all 7 scenarios are in "TechnicalAssignmentTest" class under uk.co.bbc.application(androidTest) 

5. Test script details : 

	a. Test script class name : "TechnicalAssignmentTest"
	b. Test Script package name : "uk.co.bbc.application"

6.⁠ ⁠Run the below command to execute the test cases and run the project in Gradle

a. cd ~/Android 
b. Run entire package : $ ./gradlew connectedAndroidTest
c. Run TechnicalAssignmentTest class : $ ./gradlew connectedAndroidTest -Pandroid.testInstrumentationRunnerArguments.class=uk.co.bbc.application.TechnicalAssignmentTest
 ⁠	
Other command reference :
	$ ./gradlew test 
 ⁠	$  ./gradlew run

7.⁠ ⁠Steps to run the test using Android Studio. 
	
a. Import the project "test-technical-assessments-RamyaM"
b. Navigate to device manager and start the device
b. Navigate to "TechnicalAssignmentTest" unit under uk.co.bbc.application(androidTest)
c. Run the "TechnicalAssignmentTest" class for all 7 scenarios execution. 
	

---

Thank you

