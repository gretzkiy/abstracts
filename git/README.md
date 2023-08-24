## Добавление в стейджинг только части файла

```bash
git add -p <file>
```

<details>
  <summary>Источник</summary>

  [Git for Professionals Tutorial - Tools & Concepts for Mastering Version Control with Git](https://youtu.be/Uszj_k0DGsg)
</details>

## Git rebase onto

`git rebase --onto <newparent> <oldparent>` позволяет запустить ребейз, начиная с какого-то определенного коммита.
Этот метод удобно использовать при ребейзе нескольких веток подряд, которые зависят друг от друга.

Пример:

```bash
git rebase --onto F D
```

или

```bash
git rebase --onto F E~
```

```
             До                                После
    A---B---C---F---G (branch)        A---B---C---F---G (branch)
             \                                     \
              D---E---H---I (HEAD)                  E---H---I (HEAD)
```

Словами: изменить родителя коммита E с D на F

<details>
  <summary>Источник</summary>

  [Stackoverflow](https://stackoverflow.com/a/29916361)
</details>
