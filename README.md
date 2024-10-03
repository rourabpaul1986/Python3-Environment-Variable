
# python virtual environment setup
create environment
```bash
sudo apt update
sudo apt install python3-venv
python3 -m venv myenv
source myenv/bin/activate

```
If you don't want to activate your virtual environment everytime you open your computer, you need to edit the bashrc file
```bash
nano ~/.bashrc   # For Bash
nano ~/.zshrc    # For Zsh
```
Add venv path permenantly at the end of bashrc
```bash
source /path/to/your/virtualenv/bin/activate
```
To deactivate account
```bash
deactivate
```
