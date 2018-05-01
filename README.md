# MailChimp Exercise

This was developed using Eclipse version: Neon.1a Release (4.6.1), executed against the Chrome browser Version 65.0.3325.162 (Official Build) (64-bit), using Java version 1.8.0_91.

To run:

- C:\Drivers\chromedriver
- java -jar chimp.jar

Run output:

Starting ChromeDriver 2.35.528161 (5b82f2d2aae0ca24b877009200ced9065a772e73) on port 10179
Only local connections are allowed.
Apr 26, 2018 1:36:32 PM org.openqa.selenium.remote.ProtocolHandshake createSession
INFO: Detected dialect: OSS
Failure(s): 0
Run Count: 1

Output file located at C:/MailChimp/results/bios.csv

Notes:
- I wanted to use TestNG but kept it simple using Junit .
- Need to use tab instead of comma delimitation. There were commas in the description bio.
- Thought about using asserts but for this exercise I didn't.

