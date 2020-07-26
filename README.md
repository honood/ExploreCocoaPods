# Explore CocoaPods

## How to explore CocoaPods with [RubyMine](https://www.jetbrains.com/ruby/)?

1. Clone the repo:
    
    ```sh
    git clone https://github.com/HoNooD/ExploreCocoaPods.git
    ```

2. Install gem dependencies:
    
    ```sh
    cd ExploreCocoaPods
    bundle install
    ```
    
    **NOTE:** Please make sure that [RVM](https://rvm.io/) has been installed.

3. Open `ExploreCocoaPods` with RubyMine, and add a breakpoint on the first statement of `Pod::Command::Install#run` in `cocoapods/command/install.rb` file.

4. Run “Run/Debug 'debug-cocoapods'” menu command.
    
    **NOTE:** If you were asked:
    > The debugging gems are not installed. Would you like to install them?
    
    Please select “YES”.
    
    **NOTE:** If you got the following error, please CLOSE and REOPEN the project with RubyMine.
    > Error running 'debug-cocoapods': Cannot start process, the working directory '$MODULE_DIR$' does not exist
