# Dict-for-R


## How to Use
```r
## initialize the dict(actually it is a new environment in R)
my_dict <- new.env()

## 2 ways to Assign key-value
my_dict$foo <- "bar"
word="answer"
my_dict[[word]] <- 42

## 2 ways to Call by key
my_dict$answer
# [1] 42
word="foo"
my_dict[[word]]
# [1] "bar"
```

## Performance
Like python dict, which has O(log n) performance than O(n)  
For the performance test report, see [NewDictStructure.pdf](https://github.com/jokerkeny/Dict-for-R/blob/master/NewDictStructure.pdf)

## Reference
https://www.reddit.com/r/rstats/comments/4am1x6/a_pythonlike_dictionary_data_structure_for_r/#bottom-comments

## Related Project

https://github.com/mkuhn/dict  
https://github.com/nathan-russell/hashmap  
https://cran.r-project.org/web/packages/hash/index.html  
