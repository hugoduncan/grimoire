Takes a function f and fewer than the normal arguments to f, andreturns a fn that takes a variable number of additional args. Whencalled, the returned function calls f with args + additional args.