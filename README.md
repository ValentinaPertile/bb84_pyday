# Programando qubits con Python

Código de la charla **«Programando qubits con Python»** (PyDay La Plata 2026), de Valentina Pértile de la Vega.

El ejemplo es BB84, un protocolo donde espiar deja huellas, pero lo importante son los conceptos: qubit, medición, compuertas y bases, y cómo se aplican en código.

## Qué hay en el notebook

1. Un qubit desde cero, con NumPy (una clase `Qubit`).
2. Dos bases con Qiskit.
3. BB84 sin espía: 0 % de errores.
4. BB84 con Eve: alrededor de 25 % de errores.
5. Bonus: BB84 sin espía pero con el ruido de una computadora real (1–2 % de errores).

## Cómo correrlo

```bash
pip install -r requirements.txt
jupyter notebook espia_cuantico_pyday.ipynb
```

Todo corre en el simulador de tu compu, sin internet.

¿Sin instalar nada? Abrilo en Google Colab: [abrir el notebook en Colab](https://colab.research.google.com/github/ValentinaPertile/bb84_pyday/blob/main/espia_cuantico_pyday.ipynb). La primera celda instala lo necesario si falta.

Probado con Qiskit 2.6.
