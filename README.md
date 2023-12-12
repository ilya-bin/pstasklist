# pstasklist
Task list in  with CPU % and memory in powershell based on https://superuser.com/a/1426271

# Usage
```
pstasklist.ps1 SortColumn RowsCount
```
Default sort by memory consumed descending.
To sort by CPU use
```
pstasklist.ps1 CPU
```

# Sample Output
```
Name            ID User CPU   Memory   Description                                                Title
----            -- ---- ---   ------   -----------                                                -----
idle             0      99.9% 8 K
powershell   11760      0.1%  47,280 K Windows PowerShell
serviceshell 19120      0.1%  19,272 K
ipf_helper    7444      0.1%  1,096 K  Intel(R) Innovation Platform Framework Utility Application
svchost       5640      0.1%  2,624 K
```
