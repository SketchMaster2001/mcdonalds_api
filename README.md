# McDonald's Location/Food API

Use the API to view the menu of McDonald's, and in the future find locations near you.

## Requirements

- Any version of Python 3


## Usage
This can be used in an interpreter or in python scripts. For example, I will be using this in the [WiiLink24](https://github.com/WiiLink24) revival of the Demae Channel. 

First install the dependancy which is python-dotenv.
```python
pip3 install python-dotenv
```
Then set your region by making a .env file and inputing the country code for your country.

For Canada:
```
region=ca
```

For United States:
```
region=us
```

For United Kingdom:
```
region=gb
```

Grabbing the json of
any menu category is super simple.

```python
import menu

menu.beef()
menu.mccafe()
```
etc.

I am currently working on converting the store locator.
