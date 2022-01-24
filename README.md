# LCD16X2-interfacing-with-arduino-UNO by ROBOJUNG
#include <LiquidCrystal.h>
LiquidCrystal lcd(3,4,5,6,7,8);
void setup()
{
  lcd.begin(16,2);
}
void loop()
{
  lcd.clear();
  lcd.setCursor(0,0);
  lcd.print("ROBOJUNG");
  lcd.setCursor(0,1);
  lcd.print("Like,subscribe");
  delay(100);
}
  
    
