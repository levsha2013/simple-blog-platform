# Branching Report

## Merge Statistics
- Total number of merges: 5
- Fast-forward merges: 3
- 3-way merges: 5
- Merges with conflicts: 2

## Branch History
*   c70c5ae (HEAD -> main, origin/main) Merge branch 'documentation'
|\
| * d36b4d2 (documentation) Add docs
|/
*   305bd2b Merge branch 'feature/header-update'
|\
| * 32b4fca Update header to v2.0
* | bf76820 Customize blog title
|/
*   6fb805e Merge branch 'feature/design'
|\
| * 2b494b7 Improve design and add navigation
* | 644e9f2 Add comments section
|/
* ebcf95d Add posts page and functionality
* 2af8c65 Initial project setup

## Lessons Learned
Это круто, немного поднятул практику
Вроде как конфликтов было больше(2)
Всего merge больше, чем дает git log --merges --oneline, потому что ff он как будто не отображает
И вроде все merge в git являются 3-way поэтому их столько жe, сколько всего mergees - 5