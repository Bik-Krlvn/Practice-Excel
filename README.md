# Basic Formula in excel

## Structure of functions
```console
 = FUNCTION NAME (ARGUMENTS)

```

## Sum

```console
 =SUM(TargetCellStart : TargetCellEnd)

```
## Average
```console
=AVERAGE(TargetStart : TargetEnd)

```

### Min
> finds the minimum value
```console
=MIN(TargetStart : TargetEnd)
```

### Max
> finds the maximum value
```console
=MAX(TargetStart : TargetEnd)
```

### Count
> count the total numeric values in the row
```=COUNT(TargetStart: TargetEnd)
```

### CountA
> count the total non empty cells in the row
```=COUNTA(TargetStart: TargetEnd)
```
### CountBlank
> count the total blank cells in the row
```=COUNTBLANK(TargetStart: TargetEnd)
```

## NB
Make use of the fill handles, by dragging over
to target cell, which will apply the formulars
respectively

## Excel uses Order of Operations
1. P	arentheses ()
1. E 	xponents (x) ^ 2
1. M 	ultiplication *
1. D	ivision /
1. A	addition +
1. S	ubtraction -

## NB 
If your calculation is not correct, click the fumular
tab and select evaluate formula to see what order excel
is using to make the results


## CELL References
> there are two types of references in excel
* Relative
* Absolute

## Relative Refrence
> Is when you copy a cell value/ formula to another cell.
> it moves the rows/columns and apply formular/values to the
> target.

## Absolute Reference
> Is actually making a reference cell constant.
> To make a cell constant you add a '$' before cell letter
and before the cell number. apply a shorcut with F4 to get
a constant
> example
```console
  $A$1

```

## Adjusting Excel Worksheet
### Moving existing data 
> To move an existing dataset without missing up 
>functions. highlight all the data and move your cursor to the right end of the selected border, your cursor should change to the MOVE cursor allowing you to move to any part of the screen without missing the formulars and references (Relative and Absolute)

---
> Can also use Ctrl + X and Ctrl + V to move the dataset as well

### Copying Data
> Highlight on the dataset and use the Ctrl + C 
> and Ctrl + V to make a duplicate copy of the data

### Highlight entire rows and columns
> To highlight a row use Shift + 'SpaceBar' and to highlight a column use Ctrl + 'SpaceBar'
### Inserting & Deleting a row
> Highlight the current row you want to insert a with shortcut Shift + 'SpaceBar' or use cursor and use Ctrl + '+' and Ctrl + '-' to remove a row

### Adjusting width and column space
> if your cell data exceed it space and want to resize the cell, move the cursor to the right end side of the cell at the top and just double click to auto adjust the cell.
---
> Can also select all the dataset and just double click the top of the cell to auto fix the width of all the cell in the selected field

**NB**
> Numeric values change to '####' whenever the cell is too small to accomodate the value. Please don't panic that the function is not correct. just double tap the cell top to auto adjust it size correctly.
>It will only happen on numeric values not strings


### Hide & UnHide rows and columns
> To hide a row or colum select highlight on the row and right click, choose hide from the context menu to hide the target selected.
---
>To Unhide the selected, highlight between the hidden border to the left or right of another cell, the right click, choose unhide from the context menu

#### Shortcut
> Hide Colums: Ctrl + '0'
> Hide rows: Ctrl + '9'



### Adding protection to specific rows & columns
> Adding protection helps to avoid users of modifying an underlaying formula.
> By default all cells are locked by excel.
> The general idea here, is to protect the sensitive rows and columns. so highlight the unsensitive area then right click, choose cell format and click the protection tab. Unlock the cells and click review tab on the menu. choose protect sheet to protect the rest of the sensitive area from unintensional modification by users.
---
**NB**
> You can choose to add a password or not but if you enter a password remember it when needed.