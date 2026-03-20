program Branching;
uses crt;
var a: integer;
begin
clrscr;
writeln('Ответте на вопрос,Сколько пальцев на руках у человека');
readln(a);
  if a <> 10 then begin
      writeln('Неверно!');
   end else begin
      writeln('Верно!');
end;
end.
