# Install command-line tools using Homebrew
# Usage: `brewdle install Brewfile`

tap 'caskroom/versions'

# Install GNU core utilities (those that come with OS X are outdated)
# Don’t forget to add `$(brew --prefix coreutils)/libexec/gnubin` to `$PATH`.
brew 'coreutils'
# Install some other useful utilities like `sponge`
brew 'moreutils'
# Install GNU `find`, `locate`, `updatedb`, and `xargs`, `g`-prefixed
brew 'findutils'
# Install GNU `sed`, overwriting the built-in `sed`
brew 'gnu-sed', args: ['default-names']
# Install Bash 4
# Note: don’t forget to add `/usr/local/bin/bash` to `/etc/shells` before running `chsh`.
brew 'bash'
brew 'bash-completion'

# Install zsh
brew 'zsh'

# git
brew 'git'
brew 'git-flow'

# Install wget with IRI support
brew 'wget', args: ['enable-iri']

# Install more recent versions of some OS X tools
brew 'vim', args: ['override-system-vi']

# Install other useful binaries
brew 'ack'
brew 'awscli'
brew 'cmake'
brew 'docker-clean'
brew 'docker-compose'
brew 'gawk'
brew 'go'
brew 'hashpump'
brew 'htop'
brew 'hub'
brew 'kubernetes-cli'
brew 'lynx'
brew 'maven'
brew 'nmap'
brew 'nvm'
brew 'openssl'
brew 'p7zip'
brew 'pigz'
brew 'polipo'
brew 'pv'
brew 'rename'
brew 'rbenv'
brew 'ruby-build'
brew 'readline'
brew 'socat'
brew 'sqlmap'
brew 'ssh-copy-id'
brew 'tree'
brew 'ucspi-tcp' # `tcpserver` et al.
brew 'webkit2png'

# Install Casks
cask 'atom'
cask 'docker'
cask 'etcher'
cask 'gimp'
cask 'google-chrome'
cask 'firefox'
# cask 'intellij-idea'
cask 'iterm2'
cask 'java'
cask 'kitematic'
cask 'ngrok'
cask 'omnidisksweeper'
cask 'proxpn'
cask 'silverlight'
cask 'slack'
cask 'spotify'
cask 'virtualbox'
cask 'visual-studio-code'
cask 'vlc'
cask 'vnc-viewer'
cask 'xquartz'
cask 'wireshark'
