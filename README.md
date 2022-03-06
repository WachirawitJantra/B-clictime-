#https://github.com/WachirawitJantra
import pyautogui
import pyautogui
import time
import requests

# ตัวเเปล
i = 100000
py = pyautogui
pyi = pyautogui


# คำสั้ง
while i<=5 :
    pyautogui.click(-1145,248)     #clic klogin
    time.sleep(1)

    while True:
         pyautogui.click(-1144,205)     #clic kconnegt
         pyautogui.click
         time.sleep(10)

         pyautogui.click(-964,521)      #click MetaMask
         pyautogui.click(-964,521)
         time.sleep(10)

         pyautogui.click(-1141,168)      #click press in
         pyautogui.click
         time.sleep(1)

         pyautogui.click(-1150,282)      #click character1
         time.sleep(3)

         pyautogui.click(-1150,282)      #click character2
         time.sleep(3)

         pyautogui.click(-1149,267)      #click Aotive
         time.sleep(3)

         pyautogui.click(-1189,79)      #click Aotive
         time.sleep(1)

         pyautogui.click(-1197,74)      #click all
         pyautogui.click
         time.sleep(3)

         pyautogui.click(-1124,61)      #click exit
         time.sleep(1)

         pyautogui.click(-1143,180)      #click on
         pyautogui.click
         time.sleep(1)

         
         #BOT2
         pyautogui.click(-1639,247)     #clic klogin
         time.sleep(1)
         
         pyautogui.click(-1659,210)     #clic kconnegt
         time.sleep(3)

         pyautogui.click(-1497,519)      #click MetaMask
         pyautogui.click   
         time.sleep(10)

         pyautogui.click(-1671,168)      #click press in
         pyautogui.click
         time.sleep(10)

         pyautogui.click(-1671,288)      #click character1
         time.sleep(3)

         pyautogui.click(-1672,275)      #click character2
         time.sleep(3)

         pyautogui.click(-1714,81)      #click Aotive
         pyautogui.click
         time.sleep(3)

         pyautogui.click(-1646,58)      #click all
         pyautogui.click
         time.sleep(3)
         
         pyautogui.click(-1660,191)      #click exit
         pyautogui.click
         time.sleep(1)

         pyautogui.click(-1734,45)      #click on
         time.sleep(600)
         
         pyautogui.click(-1659,210)      #click เกมหลุด
         pyautogui.click
         pyautogui.click(-1148,212) 
         pyautogui.click
      
      
      
      #เเคบจอ   
pyautogui.screenshot(str(i)+".PNG")
i+=1
time.sleep(600)
   # ล่งลาย
def linenotify(message):
  url = 'https://notify-api.line.me/api/notify'
  token = 'WNVXAUH3qVyjmjBNs3qRMYAV5HTiroWVHZn53QZEO07' # กระเป๋า
  img = {'imageFile': open('3.PNG','rb')} #ชื่อไฟล์
  data = {'message': message}
  headers = {'Authorization':'Bearer ' + token}
  session = requests.Session()
  session_post = session.post(url, headers=headers, files=img, data =data)
  print(session_post.text) 
  
message = 'คบ 10 นาทีเเล้วสิ' #คำพูด
linenotify(message)
