# HumanLikeBehaviour
 Recreating human-like behaviour for game AI

## Tensorboard
**Note: as of UE 5.5, you may come across and issue where the plugin fails to find tensorboard within the Engine files, so to fix this we'll have tensorboard installed within the project files instead of the Engine files**
### Installation
1. (Optional) open the project in Unreal to generate the required `Intermediate` folder
2. within the project directory `{Path to PROJECT}` navigate to the following directory `\Intermediate\PipInstall\Scripts`
```sh
{Path to PROJECT}\Intermediate\PipInstall\Scripts
```

3. run the following pip command to install tensorboard
```sh
./python -m pip install tensorboard
```

### Run
1. go to the following directory
```sh
{Path to PROJECT}\Intermediate\PipInstall\Scripts
```

2. run the following command
```sh
tensorboard --logdir={Path to PROJECT}\Intermediate\LearningAgents\TensorBoard\runs
```
