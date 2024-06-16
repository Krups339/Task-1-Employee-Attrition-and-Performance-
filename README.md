import seaborn as sns
import matplotlib.pyplot as plt

# Are churned customers likely to make more customer service calls?
plt.figure(figsize=(8, 6))
sns.boxplot(x='Churn', y='Customer service calls', data=data)
plt.xlabel('Churn')
plt.ylabel('Customer Service Calls')
plt.title('Churn vs. Customer Service Calls')
plt.show()
