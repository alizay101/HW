# Chapter 10 Exercises

This repository contains programming exercises for working with data frames in R, 
based on Chapter 10 of [_Programming Skills for Data Science_](https://programming-for-data-science.github.io/).
 
Solutions can be found in the `solution` branch.

Alizay tries----

name <-c("liza", "lila", "boba")

 A vector of heights
height <- c(64, 74, 69, 69, 71)

Alizay tries----

height <- c(78, 77, 90, 110)
  

A vector of weights
weight <- c(135, 156, 139, 144, 152)

Alizay tries----
  
weight <- c(145, 12, 180, 670)
  
145 

1

"liza"

name
weight 
height 

 Combine the vectors into a data frame
 Note the names of the variables become the names of the columns!
people <- data.frame(name, height, weight, stringsAsFactors = FALSE)

Alizay tries----

 Create a data frame of names, weights, and heights,
 specifying column names to use
people <- data.frame(
  name = c("Ada", "Bob", "Chris", "Diya", "Emma"),
  height = c(64, 74, 69, 69, 71),
  weight = c(135, 156, 139, 144, 152)
)

Alizay tries

people <- data.frame(
  name = c("liza", "lila", "boba"), 
  height = c(64, 74, 69, 69, 71)
  weight = c(145, 12, 180, 670)
)

people <- data.frame(
  name = c("liza", "lila", "boba"),
  height = c(64 , 74, 69, 71),
  weight = c(135, 156, 144, 152)
)

  
  
Retrieve information fromght, weight, stringsAsFactors = TRUE)

Alizay tries----

people <- data.frame(name, height, weight, stringsAsFactors = FALSE)

 Retrieve the `weight` column (as a list element); returns a vector
people_weights <- people$weight

Alizay tries----
  
people_weights <- people$weight
  

 Retrieve the `height` column (as a list element); returns a vector
people_heights <- people[["height"]]

Alizay tries----
  
people_heights <- people[["height"]]
 
