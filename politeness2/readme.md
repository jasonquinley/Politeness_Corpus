#CLS2: The Updated Classifier

The original classifier prints two probabilities for every sentence as follows: 

\{"Could you please play some Sigur Ros?" : \[.7, .3\] \}

I'm not great with messy outputs, I've rewritten some of their classifier's code to make the output a little prettier. Hope you like it! 

\{"Could you please play some Sigur Ros?" : .7 \}

This works identically to the original, but you'd type: 

cls2.predict("Could you please play some Sigur Ros?")
