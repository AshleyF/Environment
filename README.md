# Environment Setup

## Ubuntu 20.04.2 ARM

- Colmak Keyboard: `setxkbmap us -variant colemak`
- Git:
  `sudo apt install -y git`
  `git config --global user.email "ashleyf@briefrobotics.com"`
  `git config --global user.name "AshleyF"`
- oh-my-zsh:
  `sudo apt install -y curl zsh git`
  `sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`
- .NET on x86 (doesn't work on ARM):
  ```
  wget https://packages.microsoft.com/config/ubuntu/21.04/packages-microsoft-prod.deb -O packages-microsoft-prod.deb
  sudo dpkg -i packages-microsoft-prod.deb`
  rm packages-microsoft-prod.deb`

  sudo apt-get update; \
  sudo apt-get install -y apt-transport-https && \
  sudo apt-get update && \
  sudo apt-get install -y dotnet-sdk-6.0
  ```

## macOS Monderey

## Windows 11
