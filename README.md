# Palvelinten hallinta kurssin materiaalit/tehtävät

https://terokarvinen.com/2024/configuration-management-2024-spring/

### Tunnilta koodit talteen  
**sudo salt-call --local -l info** = -l info Lisää info osion  
**sudo salt-key -A** = Hyväksy avaimet  
**sudo salt '*' test-ping** = Testaa ping  
**ssh-keygen -C "Teho-pc"** = -C vaihtaa nimimerkkiä  
**git add . && git commit -m "Lisätty tekstitiedosto" ; git pull && git push**  
**grep -ri hakusana**  
**makefile** Pääkansioon  
**find -printf '%T+ %p\n' | sort** = CSI kerava = etsii sisällön = aika ja polku  
**Tekojärjestys Package -> Service -> File**  
**Koodijärjestys Package -> File -> Service**  
**salt-call --local state.apply hello --file-root C:/salt** = Windowsissa saltin ajo, tässä on polkuna c:\salt\hello
**sudo ss -lptn** = avoimet portit