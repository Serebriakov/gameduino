Arduino based handheld game with Nokia 5110 display.
Parts list:
1) Arduino nano;
2) Cheap USB PC game controller;
3) Nokia 5110 display;
4) 64KB I2C EEPROM (to store information like level maps and high scores for different games);
5) 2 Li-ION 3.7V cells.

Idea is to incorporate multiple games:
1) Sokoban - about 70% of coding completed;
2) Snake;
3) Break a block;
4) Tanks;
5) Tetris;
6) Pacman;

Currently the main problem is program memory of arduino. Nano has only 32KB, so it will be able to store only 2-3 games.