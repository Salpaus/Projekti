# Lämpömittari

  # Kehitystiimi:
  Juuso
  Juho
  
  # Asiakaskertomus
  
  1) Tee kytkentä
  2) Tarkista vastus
  3) Piirrä piirikuvio
  4) Komponenttilista, hinta
  5) Yhdistä wifi
```
int led1 = D0;

int led2 = D7;

int led3 = D3;

void setup() {

  pinMode(led1, OUTPUT);
  pinMode(led2, OUTPUT);
  pinMode(led3, OUTPUT);
}

void loop() {
  digitalWrite(led1, HIGH);
  delay(1000);
  digitalWrite(led2, HIGH);
  delay(1000);
  digitalWrite(led3, HIGH);
  delay(1000);

  digitalWrite(led1, LOW);
  delay(1000);
  digitalWrite(led2, LOW);
  delay(1000);
  digitalWrite(led3, LOW);

  delay(1000);
}
```
![20210924_125430](https://user-images.githubusercontent.com/91182746/134656264-5bf80829-55d0-4a2f-9462-c7e6c5dedc4d.jpg)
