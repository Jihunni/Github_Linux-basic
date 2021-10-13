general code
```
conda info --envs
conda env list
conda init [shell_Name]
conda create --name [virtual_env_name] --clone base
conda env remove -n [virtual_env_name]
source conda activate [env_name]
```

running code
```
conda init bash
conda activate example
```

To update conda
```
conda update conda
```

```
conda list #패키지 리스트 확인
conda install [library_name]
conda remove [library_name]
conda update [library_name]
conda update --all #
pip install [library_name]
```

# Trouble shooting
```
$ conda activate example_env
CommandNotFoundError: Your shell has not been properly configured to use 'conda activate'.
To initialize your shell, run

    $ conda init <SHELL_NAME>

Currently supported shells are:
  - bash
  - fish
  - tcsh
  - xonsh
  - zsh
  - powershell

See 'conda init --help' for more information and options.

IMPORTANT: You may need to close and restart your shell after running 'conda init'.
```
Then, Try `source conda activate example_env`

Ref:
- https://hamonikr.org/board_bFBk25/78585
- https://willbesoon.tistory.com/119