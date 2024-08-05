#SOLID #SRP #OCP 

## Термины

Программные сущность - это классы, модули, функции и тп
## SRP (Single Responsibility Principle, Принцип единственной ответственности)
#SRP 
**У каждой абстракции должна быть только одна причина для изменения**
https://www.youtube.com/watch?v=O4uhPCEDzSo&list=PLmqFxxywkatQNWLG1IZYUhKoQrnuZHqaK&index=1&pp=iAQB

## OCP (Open Closed Principle, Принцип открытости/закрытости)
#OCP

**Программные сущности должны быть открыты для расширения, но закрыты для изменения**
- **Отрыто** для расширения означает что каждая программная сущность должна быть открыта для добавления новой функциональности
![[Pasted image 20240805183011.png]]
https://www.youtube.com/watch?v=x5OtQiKOG-Q&list=PLmqFxxywkatQNWLG1IZYUhKoQrnuZHqaK&index=2&pp=iAQB

### LSP (The Liskov Substitution Principle, Принцип подстановки Барбары Лисков)
Формулировка Роберта Мартина: «функции, которые используют базовый тип, должны иметь возможность использовать подтипы базового типа не зная об этом»

Если в аргументах функции объявлен базовый тип, то наследники этого базового типа должны без всяких эксцессов работать так же как и базовый тип

Не во всех случаях возможно следовать этому правилу, например unit тестирование
![[Pasted image 20240805184443.png]]
https://www.youtube.com/watch?v=NqvwYcjrwdw&list=PLmqFxxywkatQNWLG1IZYUhKoQrnuZHqaK&index=3