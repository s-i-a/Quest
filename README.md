# Quest

Сама программа на паскале:
uses crt;
var a:string;
begin
delay(400);
writeln('Кого ебать будем?');
delay(700);
writeln('Тебя или меня?');
readln(a);
if a='тебя' 
  then writeln('Ну так еби, раз меня. Сам себя я не могу, соре')
    else if a='меня' then writeln('Хехе, готовь жеппу')
      else 
      begin 
      writeln('Че ты там промямлил? Не понимаю');
      writeln('Кого ебем-то? Четко и внятно говори: меня или тебя?');
      readln(a);
        if a='тебя' then writeln('Ну так еби, раз меня. Сам себя я не могу, хехе')
        else writeln('Хехе, готовь жеппу');
        end;
      delay(10000)
end.
