### Analysis Done in Excel



**Step1**: In the column of `F2` the data from `A` and `C` was concatenated (merged with a seprator ":") <br>
<br>
**Formula** <br>
`=CONCATENATE(A3,":",C3)` Double click the cell to repeat across `F column` 

<img src='img/Screenshot (5).png'>

<br>

<img src='img/Screenshot (6).png'>

**Copy Paste** (`as values`) **the data of** `F column` **to** `H Column`: <br>
<img src='img/Screenshot (7).png'>


**Step2**: Next, select the data from `H column` and remove the duplicates so that the `genes repeated in the same sample` will be removed<br>
<br>In excel `Remove Duplicates` is available under `Data`
<br>
<img src='img/Screenshot (8).png'>
<br><br>
Now the number of values in the column has reduced to `18` from `21`
<br><br>
Now Your data looks as follows:<br>
<img src='img/Screenshot (9).png'>
<br><br>
**Step3**: Gene names merged to the samples were removed by using `REPLACE` method. <br>

In excel press `Ctrl+F` go to `Replace` tab and enter `*:` so that values before the symbol `:` will be removed

<img src='img/Screenshot (10).png'>

