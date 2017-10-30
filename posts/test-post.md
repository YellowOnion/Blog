---
title: Blog Post Title
author: Daniel
description: it's a test post!
date: 1970-01-01
---

``` {.haskell .numberLines }
{-# LANGUAGE OverloadedStrings #-}

-- Some comment for formatting purposes
data SomeType = SomeType {
      murder :: String
    , danceFloor :: Int
} deriving (Show, Eq)

someFunc :: (a -> SomeType) -> [SomeType]
someFunc s = let x = x in map s

{- a multiLine
   comment
   for profit -}
main :: IO ()
main = putStrLn . show $ [1..10]
```

Fin.