# psychokid
код программы для удобного открытия сайтов/приложений путём выбора этих приложений/сайтов(python)

import webbrowser
import subprocess

#question
what = input("Что будем делать? (ютуб, стримы, вк, игры, домашка): ")

#youtube
if what == ("ютуб"):
    webbrowser.open('https://youtube.com', new=2)

#twitch
if what == ("стримы"):
    webbrowser.open('https://twitch.com', new=2)

#vk
if what == ("вк"):
    webbrowser.open('https://vk.com', new=2)

#games(fun)
if what == ("игры"):
    subprocess.Popen('D:\\Steam\\steam.exe')

#homework
if what == ("домашка"):
    print("Вот список предметов, готов приступать к работе?")
    #args
    print("https://gdz.ru/class-9/russkii_yazik/barhudarov-kruchkov-9/ - русский язык")
    
    print("https://gdz.ru/class-9/algebra/kolyagin/ - алгебра")
    
    print("https://gdz.ru/class-9/english/reshebnik-spotlight-9-vaulina-yu-e/ - английский")
    
    print("https://gdz.ru/class-7/geometria/atanasyan-7-9/ - геометрия")
    
    print("https://gdz.ru/class-9/fizika/belaga/ - физика")
    
    print("https://gdz.ru/class-9/biologiya/ponomareva/ - биология")
    
    print("https://gdz.ru/class-9/literatura/korovina/ - литература")

    webbrowser.open('chrome', new=2)

    input()
