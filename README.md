# RL_2023

Official Repository for the Reinforcement Learning Course at Artificial Intelligence and Robotics (Sapienza University of Rome).

Prof. Roberto Capobianco

TAs: Andrea Fanti and Michela Proietti

Here you will find the code used during practical lessons.

Please refer to the classroom page for further information.

## Dependencies

`requirements.txt` contains all the Python libraries needed to run the
notebooks, meant to be used with Python 3.8.*. To install all of them
with pip in a single command (linux/macos) run:

`pip install -r requirements.txt`

### Differences with previous years

The code of this year uses the
[gymnasium](https://gymnasium.farama.org/) library instead of gym, which
was used in previous years. A good overview of the differences can be
found [here](https://gymnasium.farama.org/content/migration-guide/).


## Syncing the fork
In order to sync the fork and merge the new changes, add the remote by:
```bash
git remote add upstream https://github.com/KRLGroup/RL_2023.git
```
then, simply fetch from this upstream:
```bash
git fetch upstream
git checkout main
```
Now you either perform a merge or a pull:
### Merge
```
git merge upstream/main
```
### Pull
```
git pull upstream main
```
Then, finally push to your origin repo by:
```
git push origin HEAD:main
```