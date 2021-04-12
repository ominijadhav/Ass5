# Ass5
# Assignment No - 5 Using R Programming

# Title: Basic statistical commands on the dataset using R and data exploration.

# Read csv file  and print dataset
df <- read.csv("r.csv")
print(df)

# alternet method for to read csv file u
df1 = read.csv(file.choose())
print(df1)

print(ls())

# Print first six rows
print(head(df))

# Compute the mean value
mean = mean(df$AGE)
print(mean)

# Mean of Weights
mean = mean(df$WEIGHT)

# Compute the Median Value
median = median(df$AGE)
print(median)

median = median(df$HEIGHT)
print(median)

# Compute the mode value
mode = mode(df$Age)
print(mode)

mode = mfv(df$WEIGHT)
print(mode)

# Exploring data in R:
# Provides basic descriptive statistics and frequencies
summary(df)

# Open data editor
edit(df)

# Provides the structure of the dataset
str(df)


# Lists variables in the dataset
names(df)

# All rows but from last 6
head(df,n=-6)

# Last 6 rows 
tail(df)

fivenum(df)
