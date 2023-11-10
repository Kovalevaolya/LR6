# LR6

## Лабораторная работа №6

### **1-2**

*В аккаунте на сайте GitHub сделана копия в личное хранилище.*
| ![1-2](screenshots/pic_1-2.png) |
|:---:|
| *картинка 1-2* |

### **3-4**

*Проверка, установлен ли Git. Настройка клиент git, ввод данных.*
| ![3-4](screenshots/pic_3-4.png) |
|:---:|
| *картинка 3-4* |

### **5**

*Клонирование своего личного удалённого репозитория на компьютер.*
| ![5](screenshots/pic_5.png) |
|:---:|
| *картинка 5* |

### **6**

*Добавление файла через интерфейс GitHub. Подтяжка изменений в локальный репозиторий.*
| ![6.1](screenshots/pic_6.1.png) |
|:---:|
| *картинка 6.1* |

| ![6.2](screenshots/pic_6.2.png) |
|:---:|
| *картинка 6.2* |

| ![6.3](screenshots/pic_6.3.png) |
|:---:|
| *картинка 6.3* |

| ![6.4](screenshots/pic_6.4.png) |
|:---:|
| *картинка 6.4* |

### **7-8**

*Получение истории операций для каждой из веток, просмотр последних изменений.*
| ![7-8](screenshots/pic_7-8.png) |
|:---:|
| *картинка 7-8* |

### **9**

*Выполнение слияния в ветку master.*
| ![9](screenshots/pic_9.png) |
|:---:|
| *картинка 9* |

### **10**

*Удаление побочной ветки после успешного удаления.*
| ![10.1](screenshots/pic_10.1.png) |
|:---:|
| *картинка 10.1* |

| ![10.2](screenshots/pic_10.2.png) |
|:---:|
| *картинка 10.2* |

### **11**

*Несколько раз внесение изменений, их фиксация с комментариями.*
| ![11](screenshots/pic_11.png) |
|:---:|
| *картинка 11* |

### **12**

*Откат коммита, проверка.*
| ![12](screenshots/pic_12.png) |
|:---:|
| *картинка 12* |

### **13**

*Создание ветки для отчёта.*
| ![13](screenshots/pic_13.png) |
|:---:|
| *картинка 13* |

### **15**

*Получение истории операций в форматированном виде.*
| ![15](screenshots/pic_15.png) |
|:---:|
| *картинка 15* |

### **Последовательность команд в порядке выполнения:**

```bash
git --version
git config --global user.name "4216 Kovaleva O. Y."
git config --global user.email "kovaleva.olga.2004@gmail.com"
git config --list
git clone https://github.com/Kovalevaolya/LR6
cd LR6
git pull
git switch Kovalevaolya-patch-1
git switch master
git log
git switch Kovalevaolya-patch-1
git log
git switch master
git pull origin master
git merge Kovalevaolya-patch-1
git branch -d Kovalevaolya-patch-1
git push origin --delete Kovalevaolya-patch-1
mv ./new_file ./new_file.txt
git add new_file.txt
git status
git add .
git status
git commit -m "Добавлено расширение .txt"
git add new_file.txt
git status
git commit -m "Добавлены изменения в new_file.txt"
git revert HEAD
git log
git switch --create report_by_Olya
git log --pretty=format:"%Н %cd %an %s"
```
