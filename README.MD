<table style="width: 100%; text-align: left;">
  <tr>
    <td style="width: 33%;">  </td>
    <td style="width: 33%;">  </td>
    <td style="width: 33%;"> <img width="100px" heigth="100px" src="./bash.png"/> </td>
  </tr>
</table>



# HOW TO INSTALL
<p>All you need is dowload 'colores.sh' and save in a save route and bash scripts</p>


<br><br>


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

### VARIABLES
<p>To see avalible variables '$ cat' colores.sh</p>

<br><br>

### EXAMPLE USE
* In others Scripts

```bash
#!/bin/bash

. /home/user/examples/colores.sh

echo -e "\n\t ${Green}I${Color_Off} ${IRed}<3${Color_Off} ${IWhite}Git${Color_Off}${IBlack}Hub${Color_Off}\n"

```

<br>


* In others Shell

```bash
$ source /home/user/examples/colores.sh

echo -e "\n\t ${Green}I${Color_Off} ${IRed}<3${Color_Off} ${IWhite}Git${Color_Off}${IBlack}Hub${Color_Off}\n"

```