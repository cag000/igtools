#  Account IG Creator



## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

i recomended to use private network, change the network if not success to create account or wait at least one day? 


## windows 10
run on windows 10
```
  - node js install,  make environment global
  - recommend use git bash download https://git-scm.com/downloads
  
  # installation 
  recommend to use separate dir such D: or E:
  git clone https://github.com/cag000/igtools.git
  git pull origin develop
  cd igtools
  npm install
  node accountCreator.js
    - number of account : <isi jumlah akun>
    - input delay (600000)in ms : safe 50000 ~ 600000
    - choose db (Y) for mysql, (N) for txt : choose n (output akun store in txt)
  look up result_account.txt for IG account
```

## andorid recommend root user for looking for result_account.txt import to ur dekstop
run on android with termux

```
  #req
   1. termux apps store
   2. internet con (private isp recomend)
  
  #play
    termux :
      apt-get update
      apt-get upgrade
      pkg upgrade
      pkg install nano
      pkg install node
      pkg install git
      git clone https://github.com/cag000/igtools.git
      cd igtools/
      git pull origin develop
      npm install
      node accountCreator.js
    - number of account : <isi jumlah akun>
    - input delay (600000)in ms : safe 50000 ~ 600000
    - choose db (Y) for mysql, (N) for txt : choose n (output akun store in txt)
  look up result_account.txt for IG account
  
```
u want to see result_account.txt /data/data/com.termux/files/home 

## Prob
prob create account

```
  Failed Register
  Message : {
  account_created : flase,
  errors : {
  ip : [
    ' The IP address you are using has been flagged as an OPEN PROXY. If you ' +
    'believe this to be incorrect, please visit http://help.instagram.com/
    ]
   },
   status :'ok'.
   error_type : 'signup block'
```
restart network or change network, whatever is.............
## License
[MIT](https://choosealicense.com/licenses/mit/)
