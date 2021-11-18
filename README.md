# dotfiles
My Linux dotfiles (conf files)

Powerline:

mkdir -p $HOME/.config/powerline
cp -R /usr/share/powerline/config_files/* \
      $HOME/.config/powerline/

Install gitstatus:
sudo apt install powerline-gitstatus

Reload powerline daemon:
powerline-daemon --replace