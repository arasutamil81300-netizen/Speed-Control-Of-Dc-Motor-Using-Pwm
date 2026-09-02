# Speed-Control-Of-Dc-Motor-Using-Pwm
Speed Control Of Dc Motor Using Pwm

# Program
```
const int motorPin = 9;
const int potPin = A0;

void setup() {
pinMode (motorPin, OUTPUT) ;

}

void loop() {
int potValue = analogRead (potPin) ;
int pwmValue = map (potValue, 0, 1023, 0, 255);
analogWrite (motorPin, pwmValue);
}
```


# Output
<img width="1047" height="556" alt="image" src="https://github.com/user-attachments/assets/81a38c68-95d0-46d0-bcfc-80743e6e5164" />
<img width="1042" height="552" alt="image" src="https://github.com/user-attachments/assets/bec9284f-7182-439f-a786-746e4c6551b3" />

# Result
Thus, the Speed Control Of Dc Motor Using Pwm is verified


