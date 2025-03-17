# f_magic
Work in progress....

## load the jupyter/ipython cellmagic with
```python
%load_ext f_magic

```
## might need ...dunno
```python
import f_magic_helpers
```

## sending
### When u are ready to send a .md cell:
*  **save the notebook** 
*  convert it to a code cell 'Y'
*  add %%m to the top of the cell
*  run with '<Shift><Enter>'.

### what happens:
* The contents of the current cell will be parsed and appended to the .md you have specified.
* Image links will be converted to work w Silverbullet.md.
*  The linked images will copied to the directory. 
* .ipynb you are working on and the .json will be copied to the folder.
  
```
%%m

```
