import pyttsx3
engine = pyttsx3.init()
import random
engine.say("перед вами три двери. В какую зайдете?")
engine.runAndWait()
while True:
    b = input ()
    if int (b) == 1:
        engine.say("вы перед сундуком. В нем может быть что угодно.")
        engine.runAndWait()
    a = input ()
    if a == ("открыть сундук"):
        a = random.randint (0,100)
    if a > 50:
        print ("там оказалось золото. Вы получили 1 гривну")
    else:
        print ("сундук открылся и оказался пустым, но в углу на дне оказался маленький павук. Он укусил тебя и ты умер. уох.")
    if int (b) == 2:
        print ("перед вами милый дракошка, которого хочет съесть тимур пахомов")
    n = input ()
    if n == ("Ударить тимура битой"):
        import random
    n = random.randint (0,100)
    if n > 69:
        print ("Вы оглушили тимура, дракончик теперь ходит с вами")
    else:
        print ("вы не оглушили тимура.Вы бросились обратно, но дверь была закрыта и тимур перекусил вами")
    if n == ("не вмешиваться"):
        print ("тимур поел")
    if int (b) == 3:
        print ("вы оказались на уроке биологии. Вы сидите за партой и скоро ширик будет спрашивать параграф.")
