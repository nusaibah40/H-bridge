# H-bridge program code:
void setup()
{
  pinMode(7, INPUT);
  pinMode(8, INPUT);
}

void loop()
{
  digitalWrite(7, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(8, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
}

# MOSFET Trade Name:
# 2SJ118 --> pmos
# 2SK176 --> nmos
