## PyCon 2015 Presentations

**NOTE:** Presentation titles link to corresponding youtube videos. 

### ["Words, words, words": Reading Shakespeare with Python](https://www.youtube.com/watch?v=EoWG0lavg9U)
* By: [Adam Palay](http://www.adampalay.com/)
* How can we use use Python to suplement our reading of Shakespeare?
* How can we get Python to read for us?
* [Shakespeare in XLM](https://github.com/severdia/PlayShakespeare.com-XML)
* Classifier - How to tell if speech is from a tragedy or comedy?
* Bag of Words - Frequencey of all words in text

```python
rhymes = get_rhymes(sonnets)
fd = nltk.FreqDist(rhymes)
for rhyme, freq in fd.most_common(10):
 print rhyme, freq

# most common words that rhyme with 'thee'
rhymes = rhymes + [tuple(reversed(rhyme)) for rhyme in rhymes]
cfd = nltk.CondaitionalFreqDist(rhymes)
for word, freq in cfd['thee'].most_common():
 print word, freq
```

### [Machine Learning 101](https://www.youtube.com/watch?v=r-1XJBHot58)
* By: Kyle Kastner
* [iPython Notebooks and Slides](https://github.com/kastnerkyle/PyCon2015)
* Automation Spectrum: Handcrafted Rules -> Statistics -> Machine Learning -> Deep Learning
* Manifold Hypothesis - Most information is structured
* [Standford UFLDL Tutorial](http://ufldl.stanford.edu/wiki/index.php/UFLDL_Tutorial)
* [Representation Learning](https://ift6266h15.wordpress.com/)
* "If you know any jokes, just tell them in your head right now."
* [sklearn-theano](https://github.com/sklearn-theano/sklearn-theano)

### [How to Be More Effective with Functions](https://www.youtube.com/watch?v=WjJUPxKB164)
* By: [Brett Slatkin](http://www.onebigfluke.com/)
* Book: [Effective Python](http://effectivepython.com)
* Reduce visual noise with variable positional argumants `def foo(*args)`

```python
favorites = [7, 33, 99]
log('Favorite numbers', *favorites)

# Equivalent to:
log('Favorite numbers', 7, 33, 99)

# If you pass a generator with *, it will break
```
* Provide optional behavior with keyword arguments `def foo(bar=123)`
 * Allows you to add functionality over time without breaking the callers
* Enforce clarity with keyword-only arguments `def foo(*, bar=123)`
 * Everything that comes after a `*` is required to passed as a keyword
* Use keyword-only args to extend *args `def log(message, *values, seq=None)`
 * Python 2: `def log(message, *values, **kwargs)`
* Consider generators instead of returning lists `yield foo`
* Be defensive when iterating over arguments
 * Python can't tell the difference between an empty iterator and an iterator that's been exhausted
 * If you iterate over an iterator, you get the same iterator
 * If you itereate over a sequence twice, you get different iterators
 * You can create an iterable container. When you do this, you get a new iterator with every call.
```python
class LoadCities(object):

 def __init__(self, path):
  self.path = path
 
 def __iter__(self):
  with open(self.path) as handle:
   for line in handle:
    city,count = line.split('\t')
    yield city, int(count)
    
# The defensive code then becomes:
def normalize_defensive(pop):
 if iter(pop) is iter(pop):
  raise TypeError('Must be a container')
 total = ...
```

### [What can programmers learn from pilots?](https://www.youtube.com/watch?v=we4G_X91e5w)
* By: Andrew Godwin 
* Soft Failure - causes you to ignore or complete miss issues. Crash hard on serious error.
* No constant low-level warmings. If you ignore it for a week, delete the warning.
* Test to the limits. Don't completely rely on automation.
* Checklists for everything. Minimize people reliance. Reduce workload at critical times.
* Priorities: What are the key things that must be done?
* Clear command (who makes the dicusion) and communication (others always listened to).
* Blame the process not the person.
* Deadlines:
 * Don't schedule everyone at maximum
 * Always expect unknown problems
 * Ship good code rather than to a deadline

### [Data Science in Advertising: Or a future when we love ads](https://www.youtube.com/watch?v=HZTgLuOpFU8)
* By: Soups Ranjan
* 

### [Beyond PEP 8 -- Best practices for beautiful intelligible code](https://www.youtube.com/watch?v=wf-BqAjZb8M)
* By: Raymond Hettinger
*

### [How to make your code Python 2/3 compatible](https://www.youtube.com/watch?v=KPzDX5TX5HE)
* By: Brett Cannon
* 

### [Advanced Git](https://www.youtube.com/watch?v=4EOZvow1mk4)
* By: David Baumgold
* 

### [Python Concurrency From the Ground Up](https://www.youtube.com/watch?v=MCs5OvhV9S4)
* By: David Beazley
* 

### [Grids, Streets and Pipelines: Building a linguistic street map with scikit-learn](https://www.youtube.com/watch?v=MIFOTFdtK2k)
* By: Michelle Fullwood
* 

### [How to interpret your own genome using (mostly) Python](https://www.youtube.com/watch?v=jV4YMQHZmMk)
* By: Titus Brown
* 

### [Losing your Loops Fast Numerical Computing with NumPy](https://www.youtube.com/watch?v=EEUXKG97YRw)
* By: Jake VanderPlas
* 

### [Don't Make Us Say We Told You So: virtualenv for New Pythonistas](https://www.youtube.com/watch?v=Xdv7vwIIThY)
* By: Renee Chu, Matt Makai
* 

### [How to Write Reusable Code](https://www.youtube.com/watch?v=r9cnHO15YgU)
* By: Greg Ward
* 

### [Good Test, Bad Test](https://www.youtube.com/watch?v=RfR_QRoNZxo)
* By: Dan Crosta
* 

### [Learning from other's mistakes: Data-driven analysis of Python code](https://www.youtube.com/watch?v=rN0kNQLDYCI)
* By: Andreas Dewes
* 

### [Technical Debt - The code monster in everyone's closet](https://www.youtube.com/watch?v=JKYktDRoRxw)
* By: Nina Zakharenko
* 

### [Facts and Myths about Python names and values](https://www.youtube.com/watch?v=_AEJHKGk9ns)
* By: Ned Batchelder
* 

### [A Beginner's Guide to Test-driven Development](https://www.youtube.com/watch?v=ePaga05gisk)
* By: Itamar Turner-Trauring
* 

### [Other people's messy data (and how not to hate it!)](https://www.youtube.com/watch?v=_eQ_8U5kruQ)
* By: Mali Akmanalp
* 

### [Describing Descriptors](https://www.youtube.com/watch?v=h2-WPwGnHqE)
* By: Laura Rupprecht
* 

### [Make web development awesome with visual diffing tools](https://www.youtube.com/watch?v=jUUTqgzNR3M)
* By: Daniel Vanderkam
* 

### [Techniques for Debugging Hard Problems](https://www.youtube.com/watch?v=ij99SGGEX34)
* By: Alex Gaynor
* 

### [Your Brain's API: Giving and Getting Technical Help](https://www.youtube.com/watch?v=hY14Er6JX2s)
* By: Sasha Laundy
* 

### [Keynote - Jacob Kaplan-Moss](https://www.youtube.com/watch?v=hIJdFxYlEKE)
* 

### [Beyond grep: Practical Logging and Metrics](https://www.youtube.com/watch?v=gqmAwK0wNyw)
* By: Hynek Schlawack
* 

### [Interactive data for the web - Bokeh for web developers](https://www.youtube.com/watch?v=O5OvOLK-xqQ))
* By: Sarah Bird
* 

### [Performance by the Numbers: analyzing the performance of web applications](https://www.youtube.com/watch?v=UAztOuO1ANQ)
* By: Geoff Gerrietts
* 

### (Docker)
