Collection of experiments for learning reinforcement learning

## Setup

Some things need to be setup manually on mac due to m1 issues.
I'll list them here

# On mac, these may need to be run manually
`CFLAGS="-mavx -DWARN(a)=(a)" pip install nes_py gym-super-mario-bros`

`conda install pytorch torchvision torchaudio -c pytorch`
