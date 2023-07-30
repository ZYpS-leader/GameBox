# Document for GameBox
It includes some simple game made by PySimpleGui, pygame or simply Tkinter. It's not 3A Game or with Java-filed Game like Minecraft. I hope you will like it.
## CHANGES
### 2023.07.30 Ver 1.1
I started this project earlier, and til now I completed the main 6 games of it. 
The remaining problem is, when starting "game2", it will start a executable CMD. This is mainly because of I used these codes:
```python
...
  if event=='G2':
    column=...
    os.system("game2.exe --column=%s"%column)
```
I don't know how to avoid this problem. The `game2.py` can't be started as a Python File, so I can only use the pyinstaller to make it into an executable program and put it into the branch "dist/main_gamin". There is where the executable main_game.py(main_game.exe) survives. This method do help me solve the beginning problem, but it cause the new problem which I have told you on the beginng of this paragraph.
So I will work hard to solve it in the next version 1.2.. Hope to see you soon.

## Using 
The codes are just in the master branch of this repository. You can just use "python main_game.py" to start it. Remember the following statements:
- Copy game2.exe from dist to the main
- Use pip to install these packages/modules: `pysimplegui`, `pillow`, `pygame`.
- Do not delete the remaining objects, they may all be used.

You can also use the executable program in dist/main_game. It's just called "main_game.exe". Click it twice to run.
