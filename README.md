# immortality-jab
Cancer cells divide indefinitely. Here I present pseudocode for a jab that achieves equilibrium between cancer and senescence via ensuring the optimum 9000 occurrences of 
TTAGGG (Telomere): 

```python
DO {
#in case cell is cancerous
IF occurrences of “TTAGGG” in Cell Chromosomal DNA > 15000
Call SenescenceFunction()

#reset in case cell is dying
ELSEIF occurrences of “TTAGGG” in Cell Chromosomal DNA < 3000
Call ActivateTelomerase()
}
#infinity loop
WHILE count(TTAGGG) in Cell Chromosomal DNA > Zero

SenescenceFunction() {
#initialize aging process
Delete 6000x “TTAGGG” from Cell Chromosomal DNA
Where preceding GENETIC CODE is “TTAGGG”
And succeeding GENETIC CODE is “TTAGGG”
}

ActivateTelomerase() {
#effect Telomerase repairs of DNA
Append 6000x “TTAGGG” in Cell Chromosomal DNA
Where preceding GENETIC CODE is “TTAGGG”
And succeeding GENETIC CODE is “TTAGGG”.
}

