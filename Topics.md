## Rough Sheet 20/OCT

### Covered Topics
- LOESS Smoothing
- Its usage in STL
- How it performs against Double exponential Smoothing
- In a streaming platform, what is the memory requirement for each algorithm
- Trend Strength and Seasonal Stength


### Rough Sheet 20/OCT

#### Loess
STL is decomposition using LOESS.
Idea in LOESS is to find moving windows, in each window try to find the linear regression to find points, 
Now do it for everything the whole data.
But LOESS is data hungry :-( 

#### Strength

Trend Strength = 1 - (var(r)/(var(t+r)))

Senasonal Strength = 1 - (var(r)/(var(s+r)))
