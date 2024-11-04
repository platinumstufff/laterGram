# laterGram
# How to build
1. Create a folder
2. Git clone this project into it
3. Create a config.h file in the root of the folder you create with
    ```
    define SETUP_API_ID(apiId) apiId = 12345;
    #define SETUP_API_HASH(apiHash) apiHash = @"put your hash here";
    ```
    _(replace apiId and apiHash with you own)_
4. Open Telegram.xcworkspace inside laterGram folder with xcode. Use Xcode 10.
