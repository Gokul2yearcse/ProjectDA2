import matplotlib.pyplot as plt
import time

# Initialize the cloth sales data
products = ["T-shirts", "Jeans", "Dresses"]
sales = [100, 50, 30]



# Create a pie chart with the initial data
plt.figure(figsize=(6, 6))
plt.pie(sales, labels=products, autopct='%1.1f%%')
plt.title("Cloth Sales")



# Function to update and redraw the pie chart
def update_pie_chart():
# Simulate updating cloth sales data (you can replace this with actual data retrieval)
    for i in range(len(sales)):
        sales[i] += 1
    plt.clf()  # Clear the previous chart
    plt.pie(sales, labels=products, autopct='%1.1f%%')
    plt.title("Cloth Sales")
    plt.draw()



# Main program loop
while True:
    update_pie_chart()
    plt.pause(1)  

# Update and display the pie chart every second
