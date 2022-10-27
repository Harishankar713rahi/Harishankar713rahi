void setup()
{
Serial.begin(9600);
pinmode(Trig, OUTPUT);
pinmode(Echo, OUTPUT);
servo.attach(motor);
M1.setSpeed(Speed);
M2.setSpeed(Speed);
M3.setSpeed(Speed);
M4.setSpeed(Speed);
}
v
