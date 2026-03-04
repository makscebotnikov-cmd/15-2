# Домашнее задание к занятию 15.2 "`Основы Git`" - `Маховский Виктор`

### Задание 1. Знакомимся с GitLab и Bitbucket

---

`Код:`
```
cd /netology/devops-netology/
git remote add gitlab git@gitlab.com:devops-mbrhard/devops-netology.git
git push -u gitlab main
git remote -v
```

<img width="379" height="69" alt="1" src="https://github.com/user-attachments/assets/503cd7a1-f769-455d-b83c-a852f21170dc" />


<img width="791" height="496" alt="2" src="https://github.com/user-attachments/assets/50482ff9-83e9-4e7a-a16f-0fa502da5bb2" />



---

### Задание 2. Теги

---

`Код:`
```
cd /netology/devops-netology/
git tag v0.0
git tag -l
git remote -v
git push --tags origin
git push --tags gitlab

git tag -a v0.1 -m "v0.1"
git push --tags origin
git push --tags gitlab
```

<img width="581" height="205" alt="3" src="https://github.com/user-attachments/assets/ec3f0c7b-be9c-45b5-90a7-57e7dfeed9df" />


<img width="690" height="109" alt="4" src="https://github.com/user-attachments/assets/ce426a3d-18ad-4c91-bd68-9eece9606df0" />


<img width="656" height="326" alt="5" src="https://github.com/user-attachments/assets/8fec68cf-49f5-485f-8275-6c3b59f7159b" />


<img width="669" height="405" alt="6" src="https://github.com/user-attachments/assets/bdcbf94b-b559-491d-aa48-26654ba7cc27" />


---


### Задание 3. Ветки

---

`Код:`
```
cd /netology/devops-netology/
git checkout main
git log --oneline --all
git checkout df54266
git switch -c fix
git push -u origin fix

git add README.md
git commit -m "Add info from fix branch"
git push origin fix
git log --oneline --all --graph
```

<img width="549" height="156" alt="7" src="https://github.com/user-attachments/assets/e1bb4bec-d55b-4caa-976f-a8518934c264" />


<img width="516" height="174" alt="8" src="https://github.com/user-attachments/assets/c09c9315-c797-479f-afbe-f3ad20f8646e" />


<img width="543" height="146" alt="9" src="https://github.com/user-attachments/assets/72d9c3ed-a3a1-4474-adc2-cfb348b19bcd" />


---

### Задание 4. Упрощаем себе жизнь

---

Работаю в Visual Studio Code. Попробую поставить расширения

На репозиторий в GitHub: https://github.com/makscebotnikov-cmd/15-1

---
