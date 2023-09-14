<h2>Шпаргалка по Git
---  
В этом проекте я стараюсь изложить то, что понял о git из курса "основы git"

<h3>Статусы файлов в git
```mermaid
untrascked -- "git add" --> staged
staged -- "commit" --> tracked
staged --> modified
tracked --> modified
modified -- "git add" --> sataged
```