# gestures-lesson
Short data analysis of the "Gestures Around the World" lesson given during the Digital Education and Learning Analytics course (CS-411) at EPFL.

## Data
All quiz scores are in */scores* folder. Keys are student names or group names depending on the activity. The value is an array. First element is the *number of correct answers for the quiz* and its normalized version (divided by number of questions in the test).
In order to open .npy files:

```python
np.load('scores/Map_Scores.npy', allow_pickle=True).item()
```
