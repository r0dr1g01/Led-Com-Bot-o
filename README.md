# 💡 Controle de LED com Botão  

Este projeto permite controlar um **LED** usando um **botão** conectado ao **Arduino**.  
Quando o botão é pressionado, o LED acende; caso contrário, ele permanece apagado.  

## 📜 Como Funciona?  
1. O código configura um **botão** como entrada e um **LED** como saída.  
2. No **loop principal**, o Arduino verifica se o botão está pressionado (`HIGH`).  
3. Se o botão estiver pressionado (`HIGH`), o LED acende.  
4. Se o botão não estiver pressionado (`LOW`), o LED apaga.  
5. O ciclo se repete continuamente.  

![image](https://github.com/user-attachments/assets/b5d4bd76-eb4f-434a-a7c7-72141e3dabc3)

## 🔌 Esquema de Ligações  

| Componente | Pino no Arduino |
|------------|----------------|
| Botão (Sinal) | 4 |
| LED (Ânodo) | 12 |
| Botão (GND) | GND |
| LED (Cátodo) | GND |

## 📂 Docs  
O código-fonte pode ser acessado aqui:  
</> [Código](docs/Código)  

---

## 🔗 Simulação no Tinkercad
[Acesse aqui a simulação do semáforo no Tinkercad](https://www.tinkercad.com/things/j8xohzgVNEF-led-com-butao?sharecode=Ky_YHG6lHjRvrxXmP14rNT7UVlSgvldq-H64kEBStDg)


