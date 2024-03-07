# Dicoding Collection Dashboard 


## upload file dashboard.py into the google colab

## Install streamlit
```
!pip install -q streamlit
```
## install localtunnel
```
!npm install localtunnel
```

## Run password for the localtunnel
```
import urllib
print("Password/Enpoint IP for localtunnel is:", urllib.request.urlopen('https://ipv4.icanhazip.com').read().decode('utf8').strip("\n"))
```

## the output will show u an IP. Copy the IP and paste it in URL in the next step
```
Password/Enpoint IP for localtunnel is: 35.230.7.178
```
## Run steamlit app
```
!streamlit run /content/dashboard.py &>/content/logs.txt &
```

## run the localtunnel
```
!npx localtunnel --port 8501
```

## the output will show a link. press the link and paste the password for the localtunnel that u have copy
```
npx: installed 22 in 2.563s
your url is: https://shiny-signs-hunt.loca.lt
```
