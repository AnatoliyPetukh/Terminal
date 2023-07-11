##  Linux terminal (GitBash) commands Homework #1
| Задание / Task | Команда / Commands |
| ---------------|----------------|
| 1. Посмотреть где я / Check my current directory |`pwd` > `enter` |
| 2. Создать папку / Create a folder |`mkdir` dir1 > `enter` |
| 3. Зайти в папку / Go into a folder |`cd` dir1 > `enter` |
| 4. Создать 3 папки / Create 3 folders |`mkdir` sdir1 sdir2 sdir3 > `enter` |
| 5. Зайти в любую папку / Go into any folder |`cd` sdir1 > `enter` |
| 6. Создать 5 файлов (3 txt, 2 json) / Create 5 files |`touch` file1.txt file2.txt file3.txt jsonfile1.json jsonfile2.json > `enter` |
| 7. Создать 3 папки / Create 3 folders |`mkdir` ssdir1 ssdir2 ssdir3 > `enter` |
| 8. Вывести список содержимого папки / List the contents of a folder |`ls -la` > `enter` |
| 9. Открыть любой txt файл / Open any txt file |`vim` file1.txt > `enter` |
| 10. Написать туда что-нибудь, любой текст / Write anything, any text in it |`i` > `The moon so bright, the stars so high<br> the silence of night, I can't deny <br>The world's asleep, so peaceful and still <br>My mind takes flight, up on this hill<br> And in this moment, I feel fulfilled` |
| 11. Сохранить и выйти / Save and exit | `esc` > `shift+:` > `wq` > `enter` |
| 12. Выйти из папки на уровень выше / Go up one level in the folder structure |`cd ..` > `enter` |
| 13. Переместить любые 2 файла, которые вы создали, в любую другую папку / Move any 2 files that you created to any other folder | `mv` file1.txt file2.txt ../sdir2 > `enter` |
| 14. Cкопировать любые 2 файла, которые вы создали, в любую другую папку / Copy any 2 files that you created to any other folder |`cp` file3.txt jsonfile1.json ../sdir2 > `enter` |
| 15. Найти файл по имени - Find a file by name | `find` file1.txt > `enter`| 
| 16. Просмотреть содержимое в реальном времени (команда grep) изучите как она работает / View real-time content (using the grep command) | `less` file2.txt > `enter` (`grep` is a mislead) | 
| 17. Вывести несколько первых строк из текстового файла / Display the first few lines of a text file | `head -3` file2.txt > `enter` | 
| 18. Вывести несколько последних строк из текстового файла / Display the last few lines of a text file | `tail -4` file2.txt > `enter` | 
| 19. Просмотреть содержимое длинного файла (команда less) изучите как она работает / View the content of a long file (using the less command), learn how it works | `less -s` file2.txt > `enter` | 
| 20. Вывести дату и время / Display the date and time | `date -u` > `enter` | 
| 21. Отправить http запрос на сервер. - Send an HTTP request to a server | `curl` http://162.55.220.72:5005/terminal-hw-request|

### Skript
Написать скрипт который выполнит автоматически пункты 3, 4, 5, 6, 7, 8, 13<br>
Write a script that will automatically perform steps 3, 4, 5, 6, 7, 8, 13

`touch` script  
`vim` script
>cd dir1<br>
mkdir sdir1 sdir2 sdir3<br>
cd sdir1<br>
touch file1.txt file2.txt file3.txt jsonfile1.json jsonfile2.json<br>
cd ..<br>
cd sdir1<br>
mkdir ssdir1 ssdir2 ssdir3<br>
ls-la<br>
mv file1.txt file2.txt ../sdir2<br>

`chmod +x` script  
./script > `enter`
