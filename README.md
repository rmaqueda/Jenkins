## Jenkins Installation


### Homebrew
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

### Java
```
brew install java11
echo 'export PATH="/usr/local/opt/openjdk@11/bin:$PATH"' >> ~/.zshrc
```

### Jenkins
```
brew install jenkins
brew services start jenkins
brew services stop jenkins
```

### Setup Jenkins services
```
vi /Users/ricardomaqueda/Library/LaunchAgents/homebrew.mxcl.jenkins.plist
```


## Pipeline iOS Tools

### Cocoapods
```
sudo gem install cocoapods
gem install cocoapods-keys
```

### Carthage
```
brew install carthage
```

### Fastlane
```
brew install fastlane
```
