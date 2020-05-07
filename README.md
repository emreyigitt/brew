# Brew App

Macos cihazlarda toplu uygulama kurulumu için brew paket yöneticisinin kurulumu 


## Brew kurulumu


```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)" 
```

## Macos tarafında uygulama kurulumları için aşağıdaki komutu kullanabiliriz.


```bash
brew cask install microsoft-office
```
```bash
brew cask install google-ads-editor
```
```bash
brew cask install firefox
```
```bash
brew cask install slack
```
```bash
brew cask install google-chrome
```
```bash
brew cask install forticlient
```
```bash
brew cask install the-unarchiver
```
```bash
brew cask install anydesk
```
```bash
brew cask install whatsapp
```
```bash
brew cask install screaming-frog-seo-spider
```
```bash
brew cask install termius
```
```bash
brew cask install spotify
```

defaults write NSGlobalDomain AppleShowScrollBars -string "Always" 
defaults write com.apple.finder AppleShowAllFiles true   
defaults write com.apple.finder ShowStatusBar -bool true 

# Default Finder location is the home folder
defaults write com.apple.finder NewWindowTarget -string "PfLo" && \
  defaults write com.apple.finder NewWindowTargetPath -string "file://${HOME}"

chflags nohidden ~/Library                             

# disable smart quotes and dashes
defaults write 'Apple Global Domain' NSAutomaticDashSubstitutionEnabled 0
defaults write 'Apple Global Domain' NSAutomaticQuoteSubstitutionEnabled 0
defaults write 'Apple Global Domain' NSAutomaticPeriodSubstitutionEnabled 0
