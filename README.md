# Python
'''
Do poszerzania umiejętności i wiedzy     
'''
import matplotlib.pyplot as plt
import numpy as np
x = np.arange(-5, 3.0, 0.01)
#y = x**3 - 2*x*2 + 1
y = x*3 - 2*x*2 + 1
#y = x**3 - 2*x**2 + 1
plt.plot(x, y)
plt.xlabel('$OX$')
plt.ylabel('$OY$')
plt.title('Wykres funkcji $x^3-2x^2+1$')
plt.grid(True)
plt.show()
