# SocialNetwork

Домашним заданием будет реализовать логику добавления в друзья в нашей социальной сети.

В нашем проекте на уровне DAL (Data Access Layer) уже реализована логика по работе с друзьями. Поэтому уровня DAL вам нет смысла касаться. 

Вашей же задачей становится добавление логики на уровень PLL и BLL. Процесс добавления пользователя в друзья должен быть следующим:
1. Пользователь вводит почтовый адрес друга.
2. Если почтовый адрес существует, то выполняем добавление.
3. Если почтового адреса не существует, то выбрасываем исключение UserNotFoundException.
4. На уровне PLL по аналогии с другими классами View создайте новую View, в которую поместите основную логику представления для добавления в друзья.
