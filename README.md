# taf-java
Test automation framework written in Java

## Instructions for macOS
1. Clone into an empty folder: `https://github.com/apuokenas/taf-java.git`, and cd into it: `cd taf-java`.
2. Check if Gradle is installed (`gradle -v`) and in your PATH (`echo $PATH`); If not, add Gradle to PATH: `export PATH=$PATH:/usr/local/opt/gradle/bin`.
3. Install Chrome WebDriver: `brew install chromedriver`, and add it to your PATH: `export PATH=$PATH:/usr/local/opt/chromedriver/bin`.
4. Download dependencies and run tests: `gradle build`.
5. Import project into IntelliJ IDEA: 
    * Import Project…
    * Import project from external model: `Gradle`
    * Use auto-import
    * Use local gradle distribution: `/usr/local/opt/gradle/libexec`
