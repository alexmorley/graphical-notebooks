#### User Action: Populate First Cell & Run

#### State: *Cell 1 [setup]*
Contents:
```
import xyz as x
import ...
```

#### User Action: Add New Cell & Populate With Loading Data Content & Run

#### State: Cell 1 [setup] & *Cell 2 [load data]*
Contents:
```
with open('data.txt', 'r') as f:
  data = read(f)
```

#### User Action: Add New Cell & Populate With Doing a Computation & Run

#### State: Cell 1 [setup] & Cell 2 [load data] & *Cell 3 [do compute]*
Contents:
```
processed_data = [d/100 for d in data]
processed_data =* 2
plt.plot(range(processed_data), processed_data)
```
Output:
```
Error: plt not defined.
```

#### User Action: Edit First Cell to include library and Execute

#### State: *Cell 1 [setup]* & Cell 2 [load data] & Cell 3 [do compute]
Contents:
```
import matplotlib.pyplot as plt
import xyz as x
import ...
```

#### User Action: Execute Cell 3

#### State: Cell 1 [setup] & Cell 2 [load data] & *Cell 3 [do compute]*
Contents: No Change
```
```
Output:  
The plot will now render at the bottom of the screen.

TODO Finish this
