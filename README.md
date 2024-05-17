# QlearningPytorch

A QLearning Demo based from the Cart example.

## Step 1 - Create Environment

We Create a virtual environment for the Demo via the Command:
```BASH

mkdir -p "./apps/"
cd ./apps/
/cygdrive/c/Data-Backup/apps/python --python="/cygdrive/c/Data-Backup/apps/python" -m venv DQN_test


#Linux

    source ./DQN_test/bin/activate
    cd ../
# Windows

     cd /DQN_test/Scripts/
     activate.bat
     cd ../../../

python -m pip install --upgrade pip
pip install pip-chill --target ./apps/DQN_test/
pip install flake8 --target ./apps/DQN_test/
pip install numpy --target ./apps/DQN_test/
pip install matplotlib --target ./apps/DQN_test/

pip install torch --target ./apps/DQN_test/

```

### Double DQN Algorithm

**Algorithm 1:** Double DQN Algorithm
**input** : #x18a -empty replay buffer; 

When $a \ne 0$, there are two solutions to $(ax^2 + bx + c = 0)$ and they are
$$ x = {-b \pm \sqrt{b^2-4ac} \over 2a} $$