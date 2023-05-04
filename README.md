# AI-MindMasterChess

It is a simple chess game which runs on flask server. It is equipped with one built-in chess engine. It has an assistant which gives the user some introduction, instructions and credits. It also warns the user when it is check and also when it is a checkmate or stalemate. But as it is running on a flask server it doesn't have any restrictions means anyone can play any move, at anytime.

# Requirements

You will have to manually executing the following commands to incorporate the requirements:

```
pip install python-chess
```

```
pip install flask
```

```
pip install pyttsx3
```

```
pip install webbrowser
```

> Don't run the following as a command.

```
Install your stockfish engine from: https://stockfishchess.org/download/
```

# Execution

Run the following code in your VS code:

```
python game-edit1.py
```

# Path Change

> 1. In the line 202: you will have to enter the path of you stockfish engine.
> 2. For MacOS you will have to download the exec file and for Windows you can download the exc version.

In the line 164: you will have to enter the path of your human.bin file for the selection of the initial move. It is included in Chess-Game.zip.

# The speak function

> 1. For MacOS: Continue using it the way it is.
> 2. For Windows: Comment out line 191 and uncomment the rest of the lines in the given function

# Features

> 1. Voice Assistant
> 2. Follows all chess rules
> 3. Two Compatible Chess Engines

# A Bug

Stockfish engine stops working if used rapidly
