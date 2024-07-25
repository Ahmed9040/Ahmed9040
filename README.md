students = ["Mahad","Ahmed","Muhammad","Hussain"]
Marks = [793,999,898,560]
plt.figure(figsize=(9, 6))

plt.pie(Marks, labels=students, autopct='%1.1f%%')
plt.show()
