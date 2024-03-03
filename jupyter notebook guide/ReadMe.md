# Jupyter Notebook on NextLevel: A Beginner’s Guide

Two Mode

- **Editing** mode (press “Enter” to go to editing mode)
- **Command** Mode (press “Escape” to go into Command mode)

### Useful Commands

- **Scrolling down** without mouse , go to command mode and use ***space bar***
- **Scrolling up** without mouse , go to command mode and use ***shift + space bar***
- For **creating a cell above** another cell
    - Go to command mode and press ***A*** for creating cell above
- For **creating a cell at bottom** of another cell
    - Go to command mode and press ***B***
- **Select bunch of cells**
    - Got to command mode
    - By pressing shift and arrow down key we can select cells
- **Cutting/pasting/copying a cell/cells**
    - Select bunch of cells/cell
    - Press ***X***  for cut
    - For Paste press ***V***
    - For copy press ***C***
- **Deleting a cell** press ***D*** two times and
- **Recovering a deleted cell** press ***Z***
- Converting a Cell into markdown/text cell or code cell
    - Go to command mode and press ***M*** (Markdown)
    - Go to command mode and press ***Y*** (Code)
- **Execute a cell** press ***shift+Enter***
- **Executing cells**  , select cells and press ***ctrl+Enter***
- **Merging cells**
    - Select those cells and press ***shift+M***
- **Split a cell** into two parts
    - Place the cursor on the position from where you want to split,
    - Go to command mode and press ***ctrl + shift + -***
- For auto Complete press ***tab***
- Documentation press ***shift + tab***

### Use Jupyter notebook as a command line Interface

- Type ! before executing any command in code mode will execute the command.

```python
!pip install numpy 
```

- We can use it for installing any modules
- Running git commands and for many other purposes.

### Other Utilities

For **removing warnings** from the code type

```python
import warnings
warnings.filterwarnings('ignore')
```

For **displaying all rows** in pandas

```python
pd.set_option('display.max_rows', None)
```

For **reveres** case use

```python
pd.set_option('display.max_rows', 10)
```

For **displaying all columns** in pandas

```python
pd.set_option('display.max_columns', None)
```

For reveres case use

```python
pd.set_option('display.max_columns', 10)
```

### Magic Commands

are the commands provided by Jupyter notebooks for making our work flow easy.

% is used for **line magics**. Line magic commands apply only to the rest of the line on which they are used.

%% is used for **cell magics**. Cell magic commands apply to the whole cell and must be placed on the first line. Everything below the %% command, up to the cell's end, is considered part of the command. Cell magics enable you to write more complex or multi-line commands, influencing or transforming the entire content of the cell.

1. **%time**

```python
# Example of using %time for a single line of code
%time sum(range(1000000))
```

1. **%%time**

```python
# Example of using %%time for an entire cell
total = 0
for i in range(1000000):
	total += i
print(total)
```

1. **%timeit** ( used to show detailed time taken)

```python
%timeit sum(range(1000000))
```

1. **%run** (command is used to run any module outside the jupyter file)

```python
%run sum.py
```

1. **%writefile** (write a file with the given name and extension )

```python
%%writefile example.txt
Hello, this is the first line of the file.
And this is the second line.
```

```python
%%writefile display.py
def display() :
	print ("Hello, world!")
if __name__ == __main__:
	display()
```

1. **%%html**

```python
%%html
‹div style="color: red; font-size: 20px;"›Hello, world!</div>
```

```python
%%html
<img src="https://static.remove.bg/sample-gallery/graphics/bird-thumbnail.jpg" alt="Sample Image" width="300">
```

1. %%latex (for writing scientific notations and statistical formulas)

```python
%%latex
The probability density function (PDF) of the normal distribution is given by:

\[
f(x | \mu, \sigma^2) = \frac{1}{\sqrt{2\pi\sigma^2}} e^{-\frac{(x - \mu)^2}{2\sigma^2}}
\]
```

### Amazing Jupyter Extensions

```python
!pip install jupyter_contrib_nbextensions 
!jupyter contrib nbextension install --user 
!jupyter nbextensions_configurator enable --user
```

Once you install above packages, you’ll get the following option in your jupyter and you can select some amazing extensions which can make your work flow very easy. 

![Screenshot 2024-03-03 at 3.58.29 PM.png](Jupyter%20Notebook%20on%20NextLevel%20A%20Beginner%E2%80%99s%20Guide%207b8047fd719248f0b5ee8b9da9905bfb/Screenshot_2024-03-03_at_3.58.29_PM.png)

- Table of content ( really useful for lengthy notebooks)
- Code Folding (it can fold our code)
- Hinterland (shows hints while typing)
- Execute time (shows execution time of every cell without using %%time)
- Hide Input (Hide code part and shows output only)