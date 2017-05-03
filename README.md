# censys
A simple Censys.io Python API Search

## Why
I couldn't find a python script to do a simple cenys.io query.  

## Running

**Searching Domain Name:**
```python censys.py -f www.censys.io```

**Searching Generic Terms:**
```python censys.py -f censys```

**Searching IP Space:**
```python censys.py -f 216.239.32.0/24```

## Demo
<img src="censys.gif">

## Notes
The API limit is pretty low so it may start throwing errors if you scan wide ranges. 

## Important Notice
I don't know what I am doing. I am not a programmer. I really suck at this.
