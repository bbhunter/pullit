# Pullit

Pullit is a real-time credential finder. 

### Installation

- ``` git pull https://github.com/filtration/pullit.git ```
- ``` sudo chmod +x install.sh  ```
- ``` ./install.sh ```
- ``` python ./pullit.py  ```


### Modules:

- Github
- Bitbucket (todo)
- Gitlab (todo)


### todo:

- Config file, have structure like so:
    
```
    name: 'Twitter Api Key'
    matches: 'twitter_api_key'
    regex: 'twitter_api_key=(.*?)'
    selector: 1 
```