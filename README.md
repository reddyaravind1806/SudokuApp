Web Sudoku Puzzle Game
======================

<p align="left">
<a href="https://github.com/huaminghuangtw/Web-Sudoku-Puzzle-Game"><img src="https://badges.frapsoft.com/os/v3/open-source.svg?v=103" alt="Open Source Love"></a><br/>
<a href="https://github.com/huaminghuangtw/Web-Sudoku-Puzzle-Game/releases"><img src="https://img.shields.io/github/v/release/huaminghuangtw/Web-Sudoku-Puzzle-Game.svg?display_name=tag&style=plastic&color=lightgrey"></a>
<a href="https://github.com/huaminghuangtw/Web-Sudoku-Puzzle-Game/tags"><img src="https://img.shields.io/github/v/tag/huaminghuangtw/Web-Sudoku-Puzzle-Game.svg?style=plastic&color=lightgrey"></a><br/> 
<a href="https://github.com/huaminghuangtw/Web-Sudoku-Puzzle-Game/stargazers"><img src="https://img.shields.io/github/stars/huaminghuangtw/Web-Sudoku-Puzzle-Game.svg?style=social"></a>
<a href="https://github.com/huaminghuangtw/Web-Sudoku-Puzzle-Game/fork"><img src="https://img.shields.io/github/forks/huaminghuangtw/Web-Sudoku-Puzzle-Game.svg?style=social"></a>
<a href="https://github.com/huaminghuangtw/Web-Sudoku-Puzzle-Game/issues"><img src="https://img.shields.io/github/issues/huaminghuangtw/Web-Sudoku-Puzzle-Game.svg?style=social&logo=github"></a>
<a href="https://github.com/huaminghuangtw/Web-Sudoku-Puzzle-Game/pulls"><img src="https://img.shields.io/github/issues-pr/huaminghuangtw/Web-Sudoku-Puzzle-Game.svg?style=social&logo=github"></a>
</p>

> Welcome to my Sudoku puzzle game! - An interactive web Sudoku puzzle game developed in HTML, CSS, and JavaScript.

### Live Demo
🔗 https://eloquent-eclair-402461.netlify.app/web-sudoku-puzzle-game-master/

---


### Description
Sudoku is one of the most popular puzzle games of all time.
The objective of Sudoku is to fill a 9-by-9 grid with digits from 1 to 9 such that each column, row, and box (or called "subgrid", "region", "block") contain every number in the set {1, ... , 9} exactly once.

This web application features **generating** and **solving** standard 9-by-9 Sudoku puzzles of different difficulty levels (i.e., easy, medium, and hard). For the Sudoku generating algorithm, please refer to [1]. The backtracking technique [2] is implemented as the solving algorithm here.

<p align="center">
    <img src="https://user-images.githubusercontent.com/43208378/148444472-bb6d43ae-c3cd-4b8e-b530-0f7cb2db1067.png" width=350>
</p>

---

### Test cases
A collection of test grids of various difficulty levels are present in the [`Test_Cases`](./Test_Cases) directory. These text files are used for the **initial** Sudoku boards of respective difficulty levels. When the user clicks the "Refresh puzzle" button, **random** Sudoku boards are subsequently generated via the approach proposed by Rob McGuir [1].

---

### References

[1] [A Sudoku puzzle generator and solver JavaScript library - sudoku.js](https://github.com/robatron/sudoku.js)

[2] [Wikipedia - Sudoku solving algorithms: Backtracking](https://en.wikipedia.org/wiki/Sudoku_solving_algorithms#Backtracking)

---


### License

This project is licensed under the terms of [![MIT](https://img.shields.io/github/license/huaminghuangtw/Web-Sudoku-Puzzle-Game.svg?style=flat-square&label=License&colorB=black)](./LICENSE).
