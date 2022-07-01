notas= [40, 70, 90, 95, 80, 85, 50, 70, 100]
import matplotlib.pyplot as plt
x = list(range(1, 10))
y = notas
plt.plot(x, y, marker='o')
plt.title('Gráfico de notas de Filosofia')
plt.xlabel('Provas')
plt.ylabel('Notas')
plt.show()