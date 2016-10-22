# Haskell Tutorial
### Install some Haskell!

1. Go to https://www.haskell.org/platform/
2. Download the proper install package for your platform. Yes. :raised_hands:
3. Install the downloaded package to your machine. :sunglasses:
4. Follow any additional instructions provided along the way. :books:
5. When ready, create a new file (in a new haskell directory), `first-haskell.hs`.
6. Open `first-haskell.hs` in your editor and type: 
```hs 
putStrLn "Hello, World!"
``` 
7. Save the file and in your terminal type `ghci` to begin interactive session (`:quit` , `:q` or CTRL + d to exit session).
8. Type `:load first-haskell` to load in your new file!  
<hr>

These are comments in haskell:
```hs
-- single line comment.
```
```hs
{-
multi-line comment.
-}
```
#### ghci commands
Commands within ghci begin with a single colon (:)  
For instance, `:quit` will exit ghci, and `:load` when passed into it a .hs file type, will load in its contents.  
There are single letter shorthands for these  (:q and :l) but it is recommended to be verbose to help in understanding what is going on at first.

>"We don’t write
Haskell because we’re geniuses — we use tools like Haskell because we’re
not geniuses and it helps us. Good tools like Haskell enable us to work
faster, make fewer mistakes, and have more information about what our
code is supposed to do as we read it." - Christopher Allen & Julie Moronuki
