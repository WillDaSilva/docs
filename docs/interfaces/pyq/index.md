# ![Python](../img/python.png) Using Python with kdb+ (PyQ)

<div class="fusion" markdown="1">
<i class="fa fa-superpowers"></i> A [Fusion interface](/interfaces/fusion)
</div>


PyQ brings the [Python programming language](https://www.python.org/about) to the kdb+ database. It allows developers to integrate Python and q code seamlessly in one application. This is achieved by bringing the Python and q interpreters into the same process, so that code written in either of the languages operates on the same data. 

In PyQ, Python and q objects live in the same memory space and share the same data.

## Quick start

Install `pyq`:
```bash
$ pip install pyq
```
Start an interactive session:
```bash
$ pyq
```
Import the `q` object from `pyq` and the `date` class from the standard library module `datetime`:
```python
>>> from pyq import q 
>>> from datetime import date
```
Drop to the [`q)` prompt]() and create an empty `trade` table:
```python
>>> q()
```
```q
q)trade:([]date:();sym:();qty:())
```
Get back to the Python prompt and insert some data into the `trade` table:
```q
q)\
```
```python
>>> q.insert('trade', (date(2006,10,6), 'IBM', 200))
k(',0')
>>> q.insert('trade', (date(2006,10,6), 'MSFT', 100))
k(',1')
```
(In the following we will skip `q()` and `\` commands that switch between `q` and Python.)

Display the result:
```python
>>> q.trade.show()
date       sym  qty
-------------------
2006.10.06 IBM  200
2006.10.06 MSFT 100
```
Define a function in q:
```q
q)f:{[s;d]select from trade where sym=s,date=d}
```
Call the `q` function from Python and pretty-print the result:
```python
>>> x = q.f('IBM', date(2006,10,6))
>>> x.show()
date       sym qty
------------------
2006.10.06 IBM 200
```
For an enhanced interactive shell, use `pyq` to start [IPython](https://ipython.org/):
```bash
$ pyq -m IPython
```

