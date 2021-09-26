import RPi.GPIO as GPIO
import time

SERVO = 17

GPIO.setmode(GPIO.BCM)

GPIO.setup(SERVO, GPIO.OUT)

servo = GPIO.PWM(SERVO, 50) # GPIO 17 for PWM with PWM 50Hz
servo.start(2.5) # Initalization

def rotate(rotate):
    duty = float(angle) / 10.0 + 2.5
    servo.ChangeDutyCycle(duty)
    
try:
    print("Program runs here...!")
    
    while Ture:
        angle = int( input( "Type in angle for servo motor : " ) )
        rotate(angle)
except KeyboardInterrupt:
    print( "Program will be finished..!" )
    
finally:
    print( "Program will be finished...!" )
    
    servo.stop()
    GPIO.cleanup()
    
    print( "All done" )
