# laterGram
# How to build
1. Create a folder
2. Create a config.h file in the root of the folder you create with
    ```
    define SETUP_API_ID(apiId) apiId = 12345;
    #define SETUP_API_HASH(apiHash) apiHash = @"put your hash here";
    ```
    _(replace apiId and apiHash with you own)_
3. Execute this:
  ```
  git clone https://github.com/platinumstufff/laterGram.git
  cd laterGram
  git submodule init
  git submodule update
  ```  
5. Open Telegram.xcworkspace inside laterGram folder with xcode. Use Xcode 10 and macOS installed on MacOS Extended partition.

# Credits
[Igor igkuzm Semetsov](https://github.com/igkuzm) - Fix outdated client error
