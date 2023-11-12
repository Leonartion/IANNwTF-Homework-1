I tried my best, but for now I couldn't find a fix for my code.
In line 86 the weighted sum can't be calculated, because the vectors seem to be of the wrong size (the inputs vector is of size (1,2) instead of (1,64))
When going back through the code, though, this exact vector seems to have the right shape since the Value Errors that I implemented to check the size aren't raised (line 128 and 198).
