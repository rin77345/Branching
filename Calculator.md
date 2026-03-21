program Branching;
uses crt;
var a,b,vibor: integer;
begin
  a:=0;
  b:=0;
  vibor:=0;
clrscr;
writeln('Это простейший канкулятор');
writeln('Введи 2 числа');
readln(a);
readln(b);
writeln('Введите выбор опирации 1-Сложение,2-Вычитание,3-Умножение,4-Деление');
readln(vibor);
if vibor=0 then writeln('Нет такой опирпации');
if vibor>=5 then writeln('Нет такой опирпации');
if vibor=1 then writeln(a+b);
if vibor=2 then writeln(a-b);
if vibor=3 then writeln(a*b);
if vibor=4 then writeln(a/b);
end.
