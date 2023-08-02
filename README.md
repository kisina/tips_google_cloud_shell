# To install a specific version of python

```bash
# install pyenv to install python on persistent home directory
curl https://pyenv.run | bash

# add to path
echo 'export PATH="$HOME/.pyenv/bin:$PATH"' >> ~/.bashrc
echo 'eval "$(pyenv init -)"' >> ~/.bashrc
echo 'eval "$(pyenv virtualenv-init -)"' >> ~/.bashrc

# updating bashrc
source ~/.bashrc

# install python 3.10.7 and make default
pyenv install 3.10.7
pyenv global 3.10.7

# execute
python
```

# To clean the instance

Initial documentation is available on [this link](https://cloud.google.com/shell/docs/resetting-cloud-shell?hl=fr#reset).

```bash
sudo rm -rf $HOME
```

Dans le menu cliquer sur ![image](https://github.com/kisina/tips_google_cloud_shell/assets/84073449/0dd7f4bd-6489-40d8-8e37-77e1579393e0)

Wait for a few minutes and try te reconnect. A newx fresh home repository should be available.
