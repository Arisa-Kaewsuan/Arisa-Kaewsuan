# HOW  &nbsp;TO  &nbsp;USE  &nbsp;GITHUB 👻

บทความนี้มีเนื้อหาหลัก 3 ส่วนเรียงกัน ดังนี้

  - วิธีใช้ git/github ตาม git flow เพื่อเก็บ code version ให้ย้อนดูได้ทำงานร่วมกับคนอื่นง่าย  &nbsp;:&nbsp;  อ่านได้ในพาร์ท &nbsp;"&nbsp; วิธีอัพ Project ของเราขึ้นไปเก็บบน Github &nbsp;"
    
  - วิธีใช้ github ในด้านอื่นๆ  &nbsp;:&nbsp; เช่น ควร commit หรือ push ตอนไหน ? &nbsp;/&nbsp; เขียน README ยังไง ?  &nbsp;อ่านได้ในพาร์ท&nbsp; "&nbsp; [Github Advanced](https://github.com/Arisa-Kaewsuan/Arisa-Kaewsuan/blob/main/advanceGitHub.md) &nbsp;"
    
  - คำศัพท์ต่างๆ ในบทความนี้ รวมไว้ในพาร์ท &nbsp;"&nbsp; Index &nbsp;"


<br/><br/>

👩‍💻 [&nbsp; How  &nbsp;to  &nbsp;use  &nbsp;GitHub ?](https://akexorcist.medium.com/%E0%B8%A1%E0%B8%B2%E0%B9%80%E0%B8%A3%E0%B8%B5%E0%B8%A2%E0%B8%99%E0%B8%A3%E0%B8%B9%E0%B9%89-git-%E0%B9%81%E0%B8%9A%E0%B8%9A%E0%B8%87%E0%B9%88%E0%B8%B2%E0%B8%A2%E0%B9%86%E0%B8%81%E0%B8%B1%E0%B8%99%E0%B9%80%E0%B8%96%E0%B8%AD%E0%B8%B0-427398e62f82)
----------------------------------------------------------------------------------------------------------------------------------------
  -  [วิธีอัพ Project ของเราขึ้นไปเก็บบน Github](https://www.youtube.com/shorts/r-C7s15IvDM) ⚡️

          มีหลายวิธีในการอัพ Project ของเราขึ้นไปเก็บบน Github Repository แบ่งเป็น 2 วิธีใหญ่ๆ คือ
             -  แบบใช้โปรแกรมที่มี GUI ไม่ว่าจะเป็นการใช้ GUI ของ editor ต่างๆ เช่น Eclipse หรือ  การใช้โปรแกรม github desktop
             -  และแบบใช้ command line เช่น Gitbash หรือ cmd ซึ่งเป็นวิธีพื้นฐานที่เราควรรู้
     

          1.  เปิด Gitbash หรือ cmd อย่างใดอย่างนึงขึ้นมา เปิดได้หลายวิธี เช่น
                 -  เปิดจาก vscode : ctrl + j เปิด terminal ขึ้นมา  >>  กด(+)เลือกว่าจะใช้เป็น Gitbash/ command prompt ก็ได้
                 -  เปิดจากหน้า desktop : window + r  >>  พิมพ์ cmd  เปิด command line (cmd) ขึ้นมา


     
          2.  change directory (cd) ไปยังโฟลเดอร์โปรเจค ที่เราต้องการอัพขึ้นไปเก็บไว้บน github repo โดยใช้คำสั่งเหล่านี้
                 -  cd  :  คือคำสั่ง change directory ไปยัง directory ที่ต้องการ 
                 -  dir หรือ ls  :  คือคำสั่ง list ไฟล์ทั้งหมดในโฟลเดอร์นั้นมาดูว่ามีไฟล์อะไรบ้าง  dir ใช้ใน cmd ส่วน ls ใช้ใน gitbash
                 -  cd .. หรือ cd\  :  คือคำสั่งย้อนกลับไป directory ก่อนหน้า
                 -  ls -a  :  คือคำสั่ง list ทุกไฟล์มาดู รวมพวกไฟล์ที่ถูกซ่อนด้วย



           3.  เมื่อเข้าถึง โปรเจคที่ต้องการแล้ว เราจะใช้ git ดังนี้
     
      ```git init```  &nbsp;&nbsp;:&nbsp;&nbsp;  คือคำสั่ง add ไฟล์ .git ใส่โปรเจคของเราเป็นการบอกว่าให้โปรเจคของเรา ใช้คำสั่งต่างๆของ git ได้ในโปรเจคนี้
     
     
      ```git add *```  &nbsp;&nbsp;:&nbsp;&nbsp;  คือคำสั่ง เลือกไฟล์ที่ต้องการจะ commit (บันทึกการเปลี่ยนแปลง)  สัญลักษณ์ * เป็นการบอกว่าเลือกทุกไฟล์ในโปรเจคนี้
     
     
      ```git commit -m " ข้อความเตือนความจำว่าเปลี่ยนอะไรไป "```  &nbsp;&nbsp;:&nbsp;&nbsp;  คือคำสั่ง บันทึกการเปลี่ยนแปลง โปรแกรม git จะเก็บมันเป็น version
         ให้เราย้อนดูได้ง่าย ไฟล์ commit จะอยู่บน local ถ้าเราอยากย้อนไปใช้ code เก่าที่เคย commit ไป สามารถทำได้หลายวิธีแล้วแต่ว่าเราใช้ tool อะไร เช่น
     -  ใน editor อย่าง vsocde มีฟีเจอร์ source control (ctrl + shift + g) ให้เราย้อนดูได้ง่าย
     -  github มีโปรแกรมชื่อ github desktop
     -  ถ้าใช้ cmd/gitbash จะใช้คำสั่ง ```git log``` ซึ่งจะแสดงข้อมูล ดังข้างล่างนี้
       
  <br/>
       
  > Commit   &nbsp;&nbsp;:&nbsp;&nbsp;  คือ &nbsp;&nbsp; เลขรหัสเวอร์ชั่น &nbsp;&nbsp;เช่น&nbsp;&nbsp;  085bb3bcb608e1e8451d4b2432f8ecbe6306e7e7 <br/>
  > Author  &nbsp;&nbsp;:&nbsp;&nbsp;  คือ &nbsp;&nbsp; ช่ื่อ คนที่commit &nbsp;&nbsp;เช่น&nbsp;&nbsp;  Scott Chacon&nbsp;&nbsp; <schacon@gee-mail.com> <br/>
  > Date  &nbsp;&nbsp;:&nbsp;&nbsp;  คือ &nbsp;&nbsp;วัน และเวลาที่ commit &nbsp;&nbsp;เช่น&nbsp;&nbsp;  Sat Mar 15 10:31:28 2008 -0700 <br/>
  > ข้อความเตือนความจำที่เราพิมพ์ตอน commit  &nbsp;&nbsp;:&nbsp;&nbsp;  เช่น&nbsp;&nbsp; Initial commit <br/>
       
   <br/>
       
   หรือ ใช้คำสั่ง ```git log -p``` คำสั่งนี้จะเพิ่มแสดงโค้ดเวอร์ชั่นนั้นๆ  และบอกเราว่าแก้ตรงไหนไปบ้าง แต่นิยมใช้คำสั่ง ```git show [เลขcommitเวอร์ชั่นที่เราอยากดู 6 ตัวแรก]``` เช่น ```git show 5eba8a```
     
               จะเห็นว่าค่อนข้างยุ่งยากจึงเกิดบริการอย่าง git repository ขึ้นมา เป็นบริการให้เราสามารถเก็บไฟล์ commit ของเราบน cloud ได้
     
                    -  ช่วยให้เราได้ back up file โดยการ push ขึ้นไปเก็บไว้บน github repo ก็จะรู้สึกปลอดภัยมากกว่ามีไฟล์เก็บไว้บนเครื่องเราอย่างเดียว
                       เผื่อวันนึงคอมของเราพังขึ้นมา ก็ยังสบายใจได้ว่ามีโค้ดเก็บอยู่บน github
     
                    -  ช่วยให้แยกกันพัฒนาได้ ทำให้การพัฒนาเป็นไปอย่างรวดเร็วโดยใช้ git branch
     
                    -  แชร์กับเพื่อนได้ช่วยให้ทำงานได้รวดเร็วกว่าเดิมมาก โดยการ push ขึ้นไปไว้บน github repo เพื่อนก็มา clone ไปแก้ต่อได้เลย
     
                    -  ย้อนดู code แต่ละ version ได้ด้วยการเก็บ commit และยังย้อนดูการเปลี่ยนแปลงง่ายเพราะมี UI สวยงาม ถ้าใครเคยใช้
                       source control ของ vscode หน้าตามันจะคล้ายๆกัน
     
                    -  และบริการเสริมอื่นๆ แล้วแต่ผู้ให้บริการ  เช่น  github ก็จะมีบริการอย่าง free  web  hosting หรือ CI/CD
     
                  นอกจาก github แล้วยังมีผู้ให้บริการ git repository อีกหลายเจ้าในปัจจุบัน  เช่น  gitlab  bitbucket
                  แต่  github เป็นที่นิยม เพราะ ฟรี และเป็นเหมือนแหล่ง opensource สำหรับผู้เริ่มต้นจึงแนะนำให้ ฝึก version control system (VCS)
                  หรือ  git โดยการใช้ tool อย่าง github และ cmd/gitbash   จะเป็นพื้นฐานที่ดีเวลาไปทำงาน

  <br/>

     4.  ขั้นตอนต่อไปเราจะพูดถึงวิธีการที่เราจะเอาไฟล์ commit บน local ขึ้นไปเก็บบน git repository อย่าง github

            4.1  ต้องมี account github ก่อนถึงจะใช้งานบริการ git repository ได้

            4.2  สมัครเสร็จแล้ว  >>  ให้ sign in  >>  new repository ขึ้นมา  github จะขึ้นแนะนำคำสั่งที่ใช้ทำงานกับ cmd ที่เราทำไปแล้ว
                       ก่อนหน้านี้  ดังรูป
  ![Screenshot (104)](https://github.com/Arisa-Kaewsuan/PHP_Exercise/assets/87797742/05fcaf87-3226-4040-b8ab-089d291e00fe)

            4.3  เราจะทำขั้นต่อไป คือ การ push เจ้า commit file ของเราทั้งหมดทุกไฟล์ไปเก็บไว้บน repository ที่เราสร้างขึ้นเมื่อกี้บน github
                 โดยจะมีขั้นตอน ดังนี้

  ```git branch -m  main```  &nbsp;&nbsp;:&nbsp;&nbsp;  คือคำสั่งที่บอกว่าเราจะเก็บไฟล์ commit ทั้งหมดนี้ไว้ใน branch ชื่อ main / master  ใช้ได้ทั้ง 2 ชื่อ แต่ github แนะนำให้ใช้ main ซึ่งเป็น branch หลัก ในการทำงานจริงตามหลัก git flow ที่แนะนำว่าควรให้ branch หลัก เป็นโปรแกรม version แรกของเรา ถ้าอยากพัฒนา version อื่น จะแยกไปพัฒนาใน branch อื่นแล้วค่อยมา Merge เข้ากับ branch นี้  ทำให้แบ่งงานกันไปแยกพัฒนาได้  ดังนั้นถ้าเราพัฒนาเวอร์ชั่นอื่น ต้องระวังตรงนี้ให้ดีอย่าเลือก branch ผิด โดย ใช้คำสั่งเหล่านี้ในการเช็ค ก่อนจะรีโมตแล้ว push เจ้า commit file ไปเก็บ

  - ```git branch [ชื่อ branchใหม่]```  &nbsp;&nbsp;:&nbsp;&nbsp;  เป็นคำสั่ง สร้าง branch ใหม่ขึ้นมา  เช่น  ```git branch develop```
  - ```git checkout [ชื่อ branch]``` &nbsp;&nbsp;:&nbsp;&nbsp; เป็นคำสั่ง เข้าไปใช้ branch ที่ระบุ เช่น ```git checkout develop```
  - ```git branch --delete [ชื่อ branch]``` &nbsp;&nbsp;:&nbsp;&nbsp; เป็นคำสั่งที่ใช้ ลบ branch ที่ระบุ เช่น ```git branch --delete develop```
  - ```git branch --all``` หรือ ```git branch``` &nbsp;&nbsp;:&nbsp;&nbsp; เป็นคำสั่งที่ใช้ ดู list ว่ามี branch/version อะไรบ้างใน repository/โปรเจค/โปรแกรม นี้

  ```git remote add origin [URLของหน้าrepositoryที่เราสร้าง]```  &nbsp;&nbsp;:&nbsp;&nbsp;  คือคำสั่งที่ บอกว่าเราจะ เก็บโค้ดใน git reponsitory ตามลิ้ง url ที่ระบุ

  ```git push -u origin main```  &nbsp;&nbsp;:&nbsp;&nbsp;  คือคำสั่งที่โยนโค้ดจากเครื่องเรา เข้า git repository

  ตอนนี้ถ้าเรา refresh หน้า repository จะเห็นว่ามีไฟล์โปรเจคของเราขึ้นไปเก็บแล้ว ในพาร์ทต่อไปจะมาพูดถึงการใช้งาน  Github  ในด้านอื่นๆ  ดูได้ที่ &nbsp;&nbsp; [>>> GitHub  Advanced](https://github.com/Arisa-Kaewsuan/Arisa-Kaewsuan/blob/main/advanceGitHub.md)

<br/><br/><br/>

# 💬 &nbsp; Index

   -  github repo / github repository / repo / repository cloud / web github คืออะไร ?

          ทั้งหมดนี้มีความหมายเดียวกัน  คือหมายถึง พื้นที่สำหรับเก็บ ไฟล์โค้ดโปรเจคต่างๆ ของเราบนเว็บ github
          could = internet = website

   -  local repo คืออะไร ?
     
          คือ พื้นที่สำหรับเก็บ ไฟล์โค้ดโปรเจคต่างๆ ของเราบนเครื่องคอมพิวเตอร์ของเรา

   -  git life cycle หรือ git flow คืออะไร / git ทำงานยังไง ?

           คือ วงจรการทำงานของ git
     
   -  UI กับ GUI ต่าง หรือเหมือนกันยังไง ?

           UI = GUI

   -  Directory คืออะไร ?

           directory = folder
      
   -  editor / IDE

           editer = IDE = library = Framework คือ tool ที่รวมสภาพแวดล้อมในการพัฒนา

   -  git คืออะไร ?

                   Git ถูกสร้างโดย Linus Torvalds ผู้คิดค้น Linux ในปี 2548 เป็นระบบ Version Control System (VCS) หรือเครื่องมือ
           ที่ช่วยให้เราสามารถ จัดการ  ติดตาม แก้ไข และตรวจสอบการเปลี่ยนแปลงของไฟล์ต่างๆในโปรเจคทั้งหมดได้ตลอดเวลาโดย Git จะสร้าง
           พื้นที่เก็บข้อมูลในเครื่องคอมพิวเตอร์และเป็นเซิร์ฟเวอร์ศูนย์กลางสำหรับการทำงานเพื่อให้เราสามารถกลับไปใช้โค้ดเวอร์ชันเก่าได้หากเกิดข้อผิดพลาดขึ้น 


   -  [commit hashing](https://www.deployhq.com/git/viewing-previous-commits)

   -  commit file / backup file

            commit file = backup file

   -  log คืออะไร ?

            ข้อความ debug ที่แสดงใน command line 

   -  Terminal / ssh / cmd / command line / shell / command prompt / bash script / git command คืออะไร ?

           ทั้งหมดมีความหมายเหมือนกัน คือ เป็น cmd เหมือนกัน

         

           
