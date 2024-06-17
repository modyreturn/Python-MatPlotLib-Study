import matplotlib.pyplot as plt


print()
print("Average Salary for Developers")
print()

ages_x = [25, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35] #average age

#Average Salary for python devs
py_dev_y = [45372, 48876, 53850, 57287, 63016, 65998, 70003, 70000, 71496, 75370, 83640]
plt.plot(ages_x, py_dev_y, label = "Python Devs")

js_dev_y = [37810, 43515, 46823, 49293, 53437, 56373, 62375, 64928, 67317, 68748, 73752]
plt.plot(ages_x, js_dev_y, label = "Python Devs")

#average salary for all devs
dev_y = [38496, 42000, 46752, 49320, 53200, 56000, 62316, 64928, 67317, 68748, 73752]
plt.plot(ages_x, dev_y, linestyle="--", label = "All Devs
 
plt.title("Median Salary by Age")
plt.xlabel("Ages")
plt.ylabel("Median Salary")

plt.legend() #used to add a legend to the chart.
#plt.legend(["ALl Devs", "Python Devs"]) <<- we could use it this way instead of labels

plt.tight_layout()
plt.show()
