# MacOS | Environment preparation

## Step 1: Download and install the Anaconda distribution of Python

```sh
brew install anaconda --cask
```

## Step 2: Set Environment Variables for conda

```sh
conda init zsh
```

To execute changes:

```sh
source ~/.zshrc
```

## Step 4: Install python:

```sh
brew install python
```

Add following:

```sh
echo "alias python=/opt/homebrew/bin/python3" >> ~/.zshrc
```

## Step 3: Install Docker (docker-compose already included)

```sh
brew install docker --cask
```

## Step 4: Open Docker and accept rules etc

## Step 4: Run Docker

```sh
docker run hello-world
```
