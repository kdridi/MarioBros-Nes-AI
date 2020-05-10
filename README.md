# MarioBros-Nes-AI

## Requirements

- python 3.6
- python 3.7
- python 3.8

## Installation

```sh
cd /tmp
git clone https://github.com/kdridi/MarioBros-Nes-AI.git
cd MarioBros-Nes-AI

rm -rf .env
mkdir .env

python3 -m venv --prompt "MarioBros-Nes-AI" "$(pwd)/.env"
source .env/bin/activate

pip3 install --upgrade pip

pip3 install pyglet==1.5.0
pip3 install gym-retro==0.8.0

unzip roms.zip
python3 -m retro.import "$(pwd)/.roms"
```

## Getting Started

```sh
python3 step00.py
```
