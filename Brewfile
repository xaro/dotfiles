# Make sure we’re using the latest Homebrew
update

tap phinze/cask
tap caskroom/versions

# Upgrade any already-installed formulae
upgrade

# Install GNU core utilities (those that come with OS X are outdated)
# Don’t forget to add `$(brew --prefix coreutils)/libexec/gnubin` to `$PATH`.
install coreutils
# Install some other useful utilities like `sponge`
install moreutils
# Install GNU `find`, `locate`, `updatedb`, and `xargs`, g-prefixed
install findutils
# Install Bash 4
install bash

# Install wget with IRI support
install wget --enable-iri

# Install more recent versions of some OS X tools
install vim --override-system-vi
install homebrew/dupes/grep

# Install other useful binaries
install ack
install pv
install git
install imagemagick --with-webp
install node
install pigz
install rename
install tree
install webkit2png
install zopfli
install p7zip
install zsh
#install pow

install homebrew/versions/lua52

#install mysql
install libyaml
install python

install brew-cask

# Casks
#cask install anvil
#cask install google-chrome
cask install steam
cask install iterm2
cask install sublime-text3
cask install skim
cask install android-file-transfer
cask install transmission
cask install dropbox

# Remove outdated versions from the cellar
cleanup
