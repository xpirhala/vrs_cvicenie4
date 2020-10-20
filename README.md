# Opis vypracovania
A assigment.h je mozne menit vstup podla toho ci chceme aby event bol spusteny bud pri dobeznej alebo nabeznej hrane.
   pri dobeznej nastavime makro v assigment.h:
   #BUTTON_EXTI_TRIGGER TRIGGER_FALL;

   pri nabeznej to zase bude:
   #BUTTON_EXTI_TRIGGER TRIGGER_RISE;
