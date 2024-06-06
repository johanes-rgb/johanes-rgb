import matplotlib.pyplot as plt

# Plotting the data
plt.figure(figsize=(10, 5))
plt.plot(range(1, 11), df['Terminal'], marker='o', label='Terminal')
plt.plot(range(1, 11), df['Industri'], marker='o', label='Industri')
plt.title('Kadar CO di Daerah Terminal dan Industri')
plt.xlabel('No. Sample')
plt.ylabel('Kadar CO (ppm)')
plt.legend()
plt.grid(True)
plt.show()
