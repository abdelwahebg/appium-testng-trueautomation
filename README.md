# appium-testng-trueautomation

* Install Appium 
* Create iOS Simulator
    * Open Xcode -> Open Developer Tool -> Simulator
* Get Simulator device udid 
    * Run Simuliator 
    * Run in terminal `xcrun simctl list devices | grep 'Booted'`
* Update udid in test file `exampleTest.java`
* Run test: `mvn -Dtest=exampleTest test` 
