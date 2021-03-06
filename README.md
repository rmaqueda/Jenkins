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

## Apache configuration
[Reference](https://moduscreate.com/blog/securing-jenkins-on-mac-os-x-with-lets-encrypt/)


## Pipeline iOS Tools

### Cocoapods
```
sudo gem install cocoapods
```

### Carthage
```
brew install carthage
```

### Fastlane
```
brew install fastlane
```

### Sonar
```
brew install sonar-scanner
```
Copy xccov-to-sonarqube-generic.sh to a directory in $PATH

### OTA tool

Copy ota_ipa.sh to a directory in $PATH