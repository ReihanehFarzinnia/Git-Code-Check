# Git-Code-Check

#Chat GPT :)
# Create a vector of random integers between 1 and 100
rand_ints <- sample(1:100, 10, replace = TRUE)

# Sort the vector in ascending order
rand_ints_sorted <- sort(rand_ints)

# Calculate the mean of the vector
mean_rand_ints <- mean(rand_ints_sorted)

# Calculate the standard deviation of the vector
sd_rand_ints <- sd(rand_ints_sorted)

# Create a data frame with two columns
df <- data.frame(names = c("Alice", "Bob", "Charlie", "Dave"), ages = c(23, 35, 41, 27))

# Subset the data frame to include only rows with ages greater than 30
df_subset <- subset(df, ages > 30)

# Print the first two rows of the subsetted data frame
head(df_subset, n = 2)

# Create a scatterplot of the ages in the data frame
plot(df$ages)

# Add a title and axis labels to the scatterplot
title(main = "Ages of People", xlab = "Person", ylab = "Age")

# Fit a linear regression model to the ages in the data frame
model <- lm(ages ~ names, data = df)
