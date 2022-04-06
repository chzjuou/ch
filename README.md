# Configuration of mkvirtualenv
pip install virtualenv  
pip install virtualenvwrapper

Revision in ~/.bashrc:  
export VIRTUALENVWRAPPER_PYTHON=/usr/bin/python3  
export WORKON_HOME='~/.virtualenvs'  
source ~/.local/bin/virtualenvwrapper.sh

source ~/.bashrc  
sudo cp ~/.local/bin/virtualenv /usr/local/bin
