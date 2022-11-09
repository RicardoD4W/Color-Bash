# HOW TO INSTALL
<p>All you need is dowload 'colores.sh' and save in a save route and bash scripts</p>


<br><br><br>


## HOW TO USE
<p>To use this "library" in others bash-scripts, you only must to have under the lane</p>

```bash
#!/bin/bash
```

<p>The following instruction:</p>

```bash
#!/bin/bash
. /absolute/route/colores.sh
```    

<p>And then with 'echo -e' you are alredy to use the variables</p>

<br><br>

### EXAMPLE USE

```bash
#!/bin/bash

. /home/user/examples/colores.sh

echo -e "\n\t I ${IRed}<3${Color_Off} ${White}Git${Color_Off}${IBlack}Hub${Color_Off}\n"

```