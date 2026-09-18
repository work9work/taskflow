# Git Notes 
 
## Git 
1. Git - система контроля версий. 
2. Рабочие изменения сначала находятся в working directory. 
3. Команда git add добавляет изменения в staging area. 
4. Команда git commit сохраняет изменения в локальный репозиторий. 
5. Команда git status показывает текущее состояние рабочего каталога. 
 
## Git Flow 
1. main - стабильная и релизная ветка. 
2. develop - ветка интеграции для следующего релиза. 
3. feature/* создаётся от develop и после работы сливается обратно в develop через PR. 
4. release/* создаётся от develop для подготовки релиза и сливается в main и develop. 
5. hotfix/* создаётся от main для срочного исправления и сливается в main и develop. 
 
## Git Workflow 
Daily workflow: update develop, create a feature branch, work, commit, push, and create a PR to develop. 

## Git Flow branch table

| Branch | From | To | Purpose |
|---|---|---|---|
| main | Ч | Ч | ╤Єрсшы№эр  тхЁёш  яЁюхъЄр |
| develop | main | Ч | ╚эЄхуЁрЎш  шчьхэхэшщ фы  ёыхфє■∙хую Ёхышчр |
| feature/* | develop | develop | ╨рчЁрсюЄър юЄфхы№эющ чрфрўш шыш ЇєэъЎшш |
| release/* | develop | main + develop | ╧юфуюЄютър ш ёЄрсшышчрЎш  Ёхышчр |
| hotfix/* | main | main + develop | ╤Ёюўэюх шёяЁртыхэшх ю°шсъш т ёЄрсшы№эющ тхЁёшш |