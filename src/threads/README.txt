The following changes were made to the following file to get the number of alarms generated to be 70 instead of 7.
1. Added alarm-mega.ck to add it as the new test.
2. Changed test.h header to include the new alarm test so source file can use it 
3. Changed test.c to add code that references the alarm-mega test that should be ran when test name entered is "alarm-mega".
4. Changed alarm-wait.c to include code that allows program to generate 70 alarms in alarm-mega.