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

In excel press `Ctrl+F` go to `Replace` tab and enter `:*` so that values after the symbol `:` will be removed

<img src='img/Screenshot (10).png'>
 <br>
<br> **After replacement** <br>
<img src='img/Screenshot (11).png'>
<br><br>


**Take a copy of** `H column` **and put in** `J column`: 
<br>
<img src='img/Screenshot (12).png'>
<br><br>

`Remove Duplicates` from the `J Column`:
<br>
<img src='img/Screenshot (13).png'>
<br><br><br>


**Step3**: Use `COUNTIF` formula to get the frequency of genes in a given range<br>
Formula : `=COUNTIF(H2:H22,J2:J15)` #You can change the range accordingly <br>
<img src='img/Screenshot (14).png'>
<br><br>

<img src='img/Screenshot (15).png'>
<br><br>

<img src='img/Screenshot (16).png'>
<br><br>

## Now, here you have the frequency of genes across the cohort
