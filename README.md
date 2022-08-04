hi# Arduini-sensors-analog-digital-


** arduino/ sensor  /analog /temperature 
circuit
نقوم  بتوصيل 
الدائره  موجوده  بالصور
نستخدم  الكود  
 

كود حساس  الحرارة
int An;
float C;
void setup()
{
An = 0;
C = 0;
Serial.begin(9600);
}
void loop()
{
An = analogRead(A3);
C=-40.0+(An*5.0/1023.0-0.1)100.0;
Serial.println(C);
delay(1000);
}
 نحسب   درجة حرارة  الغرفه   كما  في  link
https://www.tinkercad.com/things/9TEw4Rhs47a
  

**arduino /sensor /digital 

circuit
نقوم بتوصيل  دائره موجوده بالصور 
نستخدم  الكود 
cod

الكود البرمجي :


int Led =7;
void setup() {
  pinMode(Led,OUTPUT);
}
void loop()
{
digitalWrite(Led,HIGH);
  delay(1000);
  digitalWrite(Led,LOW);
  delay(1000);
}

يتم   تشغيل   لمبة  led    
يمكن  تجربة  الدائرة في   link  

https://www.tinkercad.com/things/1gxcGpHW9r2


