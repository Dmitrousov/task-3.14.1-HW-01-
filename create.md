[< к содержанию](./readme.md)

## Создание проекта

Чтобы создать GIT-репозиторий с нуля, выполните следующие команды:

```bash=
mkdir dir
cd dir
touch file.html
git init
```

Результат выполнения команд:

```bash=
Initialized empty Git repository in /home/user/githowto/repositories/dir/.git/
```

Чтобы добавить страницу в созданный репозиторий, выполните следующие команды:

```bash=
git add file.html
git commit -m "Initial Commit"
```

Результат выполнения команд:

```bash=
$ git add file.html
$ git commit -m "Initial commit"
[main (root-commit) 5836970] Initial commit
 1 file changed, 1 insertion(+)
 create mode 100644 file.html
```

---
Использованные команды Git:
[git init](./init.md),
[git add](./add.md),
[git commit](./commit.md).
---
