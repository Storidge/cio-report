# cio-report

 cio-report is a golang utility for pre-processing reports from `cioctl report`
- Extracts and summarizes info from report.txz
- Looks for known patterns from previous reports

### Install 

Download and save to /usr/bin
```
git clone https://github.com/Storidge/cio-report 
cp cio-report/cio-report /usr/bin
```

### Run 

Extract report.txz file and run basic report
```
tar xvf report.txz 
cio-report basic
```
