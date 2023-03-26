# Define variables
avg_purchase <- 6.45
num_purchases_week <- 3
lifespan <- 3
discount_rate <- 0.1
profit_margin <- 0.25

# Calculate CLV
CLV <- (avg_purchase * num_purchases_week * lifespan) / (1 + discount_rate - 1) * (1 + profit_margin)

# Print result
print(paste0("The estimated CLV is $", round(CLV, 2)))
