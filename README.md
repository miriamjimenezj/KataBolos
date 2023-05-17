# Sobre el proyecto 
Esta práctica consiste en la correcta realización de una de las katas más famosas de la metodología TDD (Test-Driven Development), la conocida como Kata del tanteo de los bolos.

# Reglas de la Kata
El objetivo es crear el marcador de una partida de bolos, el cual sigue las siguientes reglas:
1. Una partida de bolos dura diez rondas, en cada una de las cuales el jugador tiene uno o dos intentos para tirar diez bolos colocados formando un triángulo.
2. Si el jugador tira los diez bolos en el primer intento (esta jugada se denomina "strike"), se anota diez bolos más el número de bolos que tire en sus siguientes dos bolas.
3. Si el jugador tira los diez bolos en el segundo intento (esta jugada se denomina "spare"), se anota diez bolos más el número de bolos que tire en su próxima bola.
4. Si el jugador no tira los diez bolos (esta jugada se llama "ronda abierta" u "open frame") se anota el número de bolos que haya tirado.
5. El marcador se va acumulando en las diez rondas.
6. Tras la última ronda, si es necesario, se lanzan una o dos bolas extra para anotar el bonus final.

# Cómo ejecutar la Kata
Para ejecutar la Kata usa el siguiente código:

    make

Para limpiar una vez ejecutada la Kata:

    make clean

## Licencia
Copyright 2023 Miriam Jiménez

 Licensed under the Apache License, Version 2.0 (the "License");
 you may not use this file except in compliance with the License.
 You may obtain a copy of the License at
	
  http://www.apache.org/licenses/LICENSE-2.0
	
  Unless required by applicable law or agreed to in writing, software
  distributed under the License is distributed on an "AS IS" BASIS,
  WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
  See the License for the specific language governing permissions and
  limitations under the License
