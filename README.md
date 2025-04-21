# jupyter notebook overview

## description
![illustration of silhouetted heads](mentalhealth.jpg)

## summary
- total cells: 5
- code cells: 2
- markdown cells: 3

## how to run
1. make sure you have jupyter notebook and a sql-compatible environment (like sqlite or a jupyter sql extension).
2. open a terminal and navigate to the folder containing this file.
3. run `jupyter notebook notebook.ipynb` and follow any instructions to connect your database.

## dependencies
- a jupyter sql extension or a connection to your sql environment
- access to a `students` table with columns: `stay`, `inter_dom`, `todep`, `tosc`, `toas`

## purpose
this notebook explores how students' mental health scores vary based on their living arrangements and whether they are international. it uses sql to group and average scores like phq (depression), scs (social connection), and as (anxiety).
