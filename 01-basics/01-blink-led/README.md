# LED Blinking - Arduino Basics

**Your first Arduino project template - Add your LED blink code here**

## Learning Objectives

- [ ] Understand Arduino IDE
- [ ] Upload code to Arduino board
- [ ] Control digital output pins
- [ ] Use delay functions
- [ ] Understand blinking patterns

## Project Structure

```
01-blink-led/
├── blink.ino              # (Add your code)
├── blink-with-button.ino  # (Add: Button-controlled blink)
├── circuit_diagram.png    # (Add schematic)
└── README.md
```

## Code Template

```cpp
// Your LED blink code here
void setup() {
  pinMode(13, OUTPUT);
}

void loop() {
  digitalWrite(13, HIGH);
  delay(1000);
  digitalWrite(13, LOW);
  delay(1000);
}
```

## Your Notes

(Add your learnings here)
