[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-c66648af7eb3fe8bc4f294546bfd86ef473780cde1dea487d3c4ff354943c9ae.svg)](https://classroom.github.com/online_ide?assignment_repo_id=9315291&assignment_repo_type=AssignmentRepo)
## Task 1
Играем опростени експлодиращи котета.
В играта има X играчи и X-1 експлодиращи котета. В тестето може да има следните карти:
 * O - обикновенна карта, не прави нищо
 * B - експлодиращо коте, ако играчът няма карта "обезвреждане" губи играта. Ако се изиграе обезвреждане, котето се връща най-отдолу в колодата и чака своя нов собственик.
 * S - карта обезвреждане, играчът може да е изиграе след като изтегли експлодиращо коте и да се спаси до следващия път. След като бъде изиграна картата не се връща в колодата с карти.
 - Играчите се редуват да теглят карти, като започва първия, след него втория втория... Ако някой изтегли експлодиращо коте и не може да се спаси не тегли повече карти в текущата игра.
 - Всеки един играч играе оптимално според правилата на играта за себе си.
 - Един играч може да има неограничен брой кари обезвреждане, стига да му са се паднали.
Печели, този който остане последен в играта. Намерете кой ще спечели играта по зададето тесте с карти.

### Task 2
Разглеждаме насочен граф G, представен посредством vector от vector от тип int. 
Да се намери отговор на въпроса дали от връх From до връх To има път с помощта на BFS и какъв е минималния път като брой стъпки. Ако няма такъв да се върне -1.
Задачата да се реши без рекурсия. 

### Tasks 3
Разглеждаме шахматно поле с площ от A1 до H8. Кон се разхожда Г-образно като няма право да излиза от полето. 
По зададено начално поле и крайно да се определят минималния брой стъпки, с които коня може да стигне от началната до крайната точка.

### Task4
Разглеждаме карта на море представена като двумерен вектор. Подаденият вход гарантира, че е вектор с еднакви размери.
Клетка от море се отбелязва с 0, а къс земя се представя като 1.
Остров се дефинира като множество от късове (поне една) земя, които имат поне една обща страна (изток, запад, север, юг).
По зададена карта, да се намерят колко острова има.
