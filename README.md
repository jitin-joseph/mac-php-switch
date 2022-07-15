brew unlink php@8.0 && brew link --force php@7.4


echo 'export PATH="/usr/local/opt/php@7.4/bin:$PATH"' >> ~/.zshrc
