## PyCon 2015 Presentations

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
* 

### [How to Be More Effective with Functions](https://www.youtube.com/watch?v=WjJUPxKB164)
* By: Brett Slatkin
* 

### [What can programmers learn from pilots?](https://www.youtube.com/watch?v=we4G_X91e5w)
* By: Andrew Godwin 
* 

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
