Bibliotecas para se utilizar modulos de LCD especificos para UNO no ARDUINO MEGA!!
Apos copiar, utilize o exemplo de SWTFT SHIELD!!

O cartão SD ainda não funciona!. Caso achem solução, por favor, compartilhe!!!

Descrição:
ADAFRUIT GXF = Responsavel por ler imagens do cartao de memoria e exibi-las no LCD
SD = Responsavel por gerenciar o cartão SD
SWTFT = Responsavel por gerenciar o LCD
Touch Sceen library = Responsavel por gerenciar o TOUCH e definir o ponto onde foi tocado.

Para alternar entre arduinos, modifique a seguinte linha no arquivo SWTFT.CPP

#include "mega_24_shield.h"
//#include "uno_24_shield.h"

