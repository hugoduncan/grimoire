Takes a function f, and returns a function that calls f, replacinga nil first argument to f with the supplied value x. Higher arityversions can replace arguments in the second and thirdpositions (y, z). Note that the function f can take any number ofarguments, not just the one(s) being nil-patched.