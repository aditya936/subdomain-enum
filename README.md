# subdomain-enum
this repo is help to gather subdomains via amass [passive way] and subfinder , after gather all subdomains it auto complete into url by using httprobe. it create a main directory by domain which on working to save all work, name is simple after finish amass work save into amass.txt similarly subfinder.txt . this is written in bash so firstly install bash latest version from internet. to use this script just copy the code and save in your pc and then give permission chmod +x subdomain-enum .to access from anywhere move it to bin folder.

* how it works look
subdomain-enum.sh github.com
github.com [create dir] -> amass.txt , subfinder.txt -> 2-allsubd-github.com.txt [combine unique domains from both] -> 3-subgihub.com.txt [after applying httprobe]



how to use :- 
ex1: subdomain-enum.sh domains.txt
ex2: subdoamin-enum.sh github.com

