# picoCTF

#General Skills 

## Challenge: Tab, Tab, Attack

**Commands Used:**
```bash
Harshvardhan_kode-picoctf@webshell:~$ mkdir tabtab
Harshvardhan_kode-picoctf@webshell:~$ cd tabtab
Harshvardhan_kode-picoctf@webshell:~/tabtab$ wget https://challenge-files.picoctf.net/c_wily_courier/1d211441eced2214a10b0c2aacbf05d153aafcd6edc055f913cafcdb48a0b02b/Addadshashanammu.zip
--2026-02-14 12:19:38--  https://challenge-files.picoctf.net/c_wily_courier/1d211441eced2214a10b0c2aacbf05d153aafcd6edc055f913cafcdb48a0b02b/Addadshashanammu.zip
Resolving challenge-files.picoctf.net (challenge-files.picoctf.net)... 3.160.5.64, 3.160.5.18, 3.160.5.40, ...
Connecting to challenge-files.picoctf.net (challenge-files.picoctf.net)|3.160.5.64|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 5166 (5.0K) [application/octet-stream]
Saving to: 'Addadshashanammu.zip'

Addadshashanammu.zip  100%[=========================>]   5.04K  --.-KB/s    in 0s      

2026-02-14 12:19:38 (2.80 GB/s) - 'Addadshashanammu.zip' saved [5166/5166]

Harshvardhan_kode-picoctf@webshell:~/tabtab$ ls
Addadshashanammu.zip
Harshvardhan_kode-picoctf@webshell:~/tabtab$ unzip Addadshashanammu.zip 
Archive:  Addadshashanammu.zip
   creating: Addadshashanammu/
   creating: Addadshashanammu/Almurbalarammi/
   creating: Addadshashanammu/Almurbalarammi/Ashalmimilkala/
   creating: Addadshashanammu/Almurbalarammi/Ashalmimilkala/Assurnabitashpi/
   creating: Addadshashanammu/Almurbalarammi/Ashalmimilkala/Assurnabitashpi/Maelkashishi/
   creating: Addadshashanammu/Almurbalarammi/Ashalmimilkala/Assurnabitashpi/Maelkashishi/Onnissiralis/
   creating: Addadshashanammu/Almurbalarammi/Ashalmimilkala/Assurnabitashpi/Maelkashishi/Onnissiralis/Ularradallaku/
 extracting: Addadshashanammu/Almurbalarammi/Ashalmimilkala/Assurnabitashpi/Maelkashishi/Onnissiralis/Ularradallaku/fang-of-haynekhtnamet.c  
  inflating: Addadshashanammu/Almurbalarammi/Ashalmimilkala/Assurnabitashpi/Maelkashishi/Onnissiralis/Ularradallaku/fang-of-haynekhtnamet  
Harshvardhan_kode-picoctf@webshell:~/tabtab$ cd Addadshashanammu/
Harshvardhan_kode-picoctf@webshell:~/tabtab/Addadshashanammu$ cd Almurbalarammi/
Harshvardhan_kode-picoctf@webshell:~/tabtab/Addadshashanammu/Almurbalarammi$ cd Ashalmimilkala/
Harshvardhan_kode-picoctf@webshell:~/tabtab/Addadshashanammu/Almurbalarammi/Ashalmimilkala$ cd Assurnabitashpi/
Harshvardhan_kode-picoctf@webshell:~/tabtab/Addadshashanammu/Almurbalarammi/Ashalmimilkala/Assurnabitashpi$ cd Maelkashishi/
Harshvardhan_kode-picoctf@webshell:~/tabtab/Addadshashanammu/Almurbalarammi/Ashalmimilkala/Assurnabitashpi/Maelkashishi$
 cd Onnissiralis/
Harshvardhan_kode-picoctf@webshell:~/tabtab/Addadshashanammu/Almurbalarammi/Ashalmimilkala/Assurnabitashpi/Maelkashishi/
Onnissiralis$ cd Ularradallaku/
Harshvardhan_kode-picoctf@webshell:~/tabtab/Addadshashanammu/Almurbalarammi/Ashalmimilkala/Assurnabitashpi/Maelkashishi/
Onnissiralis/Ularradallaku$ ls
fang-of-haynekhtnamet  fang-of-haynekhtnamet.c
Harshvardhan_kode-picoctf@webshell:~/tabtab/Addadshashanammu/Almurbalarammi/Ashalmimilkala/Assurnabitashpi/Maelkashishi/
Onnissiralis/Ularradallaku$ cat fang-of-haynekhtnamet
@@@   -==X`-=888 XXXDDStd888 Ptd8 8 8 DDQtdRtd-==HH/lib64/ld-linux-x86-64.so.2GNUGNUOZP  GNUem= 
                                                                                                Y h "libc.so.6puts__cxa_finalize__libc_start_mainGLIBC_2.2.5_ITM_deregisterTMCloneTable__gmon_start___ITM_registerTMCloneTableui        @?????H/H=R/H=y/Hr/H9tH./HtPTLfHH=I/H5B/H)HH?HHHtH/HfD=/u+UH=.Ht
                                                        H=.d.]wUHH=]f.fAWL=;,AVIAUIATAUH-,,SL)_Ht1LLDAHH9u[]A\A]A^A_ff*ZAP!* picoCTF{l3v3l_up!_t4k3_4_r35t!_fc588427}D(`88zRx
                                                    $4h FJ
                                                          ?:*3$"\`tX9
R
D@eFIE E(D0H8G@n8A0A(B BBh@
op

?      oooo=@GCC: (Ubuntu 9.4.0-1ubuntu1~20.04.2) 9.4.08X|p
 

 @P` 8  ===?@@
              @F=m@y=!===8 ?
                            $ z @@R@Yx@@ pe@~`/@I "crtstuff.cderegister_tm_clones__do_global_dtors_auxcompleted.8061__do_global_dtors_aux_fini_array_entryframe_dummy__frame_dummy_init_array_entryfang-of-haynekhtnamet.c__FRAME_END____init_array_end_DYNAMIC__init_array_start__GNU_EH_FRAME_HDR_GLOBAL_OFFSET_TABLE___libc_csu_fini_ITM_deregisterTMCloneTableputs@@GLIBC_2.2.5_edata__libc_start_main@@GLIBC_2.2.5__data_start__gmon_start____dso_handle_IO_stdin_used__libc_csu_init__bss_startmain__TMC_END___ITM_registerTMCloneTable__cxa_finalize@@GLIBC_2.2.5.symtab.strtab.shstrtab.interp.note.gnu.property.note.gnu.build-id.note.ABI-tag.gnu.hash.dynsym.dynstr.gnu.version.gnu.version_r.rela.dyn.rela.plt.init.plt.got.plt.sec.text.fini.rodata.eh_frame_hdr.eh_frame.init_array.fini_array.dynamic.data.bss.comment#886XX$I|| Woa
  8 8=?@0                                                                                         ippqo~o @PP``
       @00+@0.  X6k8
```
** picoCTF flag**
```bash
picoCTF{l3v3l_up!_t4k3_4_r35t!_fc588427}
```


## Challenge: strings it

**Commands Used:**
```bash
Harshvardhan_kode-picoctf@webshell:~$ cd string
Harshvardhan_kode-picoctf@webshell:~$ wget https://challenge-files.picoctf.net/c_fickle_tempest/53c039e64942b1c4334781c4987ba7e2ba54f0b2bf39f52c65f3a65dfcbf4194/strings
Harshvardhan_kode-picoctf@webshell:~$ 
Harshvardhan_kode-picoctf@webshell:~/string$ strings strings | grep picoCTF
picoCTF{5tRIng5_1T_A1b9ECAa}
```
** picoCTF flag**
```bash
picoCTF{5tRIng5_1T_A1b9ECAa}
```


## Challenge: FANTASY CTF

**Commands Used:**
```bash
Harshvardhan_kode-picoctf@webshell:~$ nc verbal-sleep.picoctf.net 51753
FANTASY CTF SIMULATION

The simulation begins in the private room of Eibhilin, a bright, young student.
The room is dimly lit, with the glow of her multiple monitors casting an
electric blue hue on the walls. Around the room are posters of vintage movies
from the MCU — ancient guardians from another age staring down like digital
sentinels.

---
(Press Enter to continue...)
---

Eibhilin stretches back in her chair, adjusting the holo-display of her
keyboard. A soft hum of a nearby server fills the air as her AI companion,
`Nyx`, comes to life.

---
(Press Enter to continue...)
---

"Good evening, Ei," Nyx chirps, "The 3025 edition of picoCTF registration is
open. You asked me to remind so you could try out the competition for the first
time. Do you wish to proceed?"

---
(Press Enter to continue...)
---

Outside, the city of Nexalus glimmers under the stars, but Eibhilin's focus
remains entirely on the screen in front of her.

---
(Press Enter to continue...)
---

"Yes, Nyx. Let's do it!"

---
(Press Enter to continue...)
---

Nyx brings up the registration page.

Options:
A) *Register multiple accounts*
B) *Share an account with a friend*
C) *Register a single, private account*
[a/b/c] > A

Nyx chimes in, "Eibhilin, don't do that! That's been grounds for
disqualification for the past 1,000 years!"

---
(Press Enter to continue...)
---

"Oh, thanks Nyx, that was close!"

---
(Press Enter to continue...)
---

"Ok," Nyx says, "Registering you for the competition... There's an introductory
audio message, piping to your speakers."

---
(Press Enter to continue...)
---

"Welcome hacker! You're about to embark on a journey that will teach you many
esoteric and valuable skills. Our mission is to guide you in the right path,
that you may use these skills to protect and defend and never for selfish gain
or deceit. We hope you enjoy the challenges that our authors have devised this
year. Always remember: 'With great power, comes great responsibility!'"

---
(Press Enter to continue...)
---

Nyx continues, "I've gleaned from the Ether that in CTF competitions, it's
always good to start with the 'sanity' challenge. It should be the challenge
worth the least amount of points. I'll pull it up. You're looking for something
called the flag. You should know it when you see it."

---
(Press Enter to continue...)
---

"Oh interesting," Eibhilin says, "It seems like the sanity challenge is an old
school interactive fiction game."

---
(Press Enter to continue...)
---

Options:
A) *Play the game*
B) *Search the Ether for the flag*
[a/b] > A

"Good choice, Ei," Nyx says, "You never want to share flags or artifact
downloads."

---
(Press Enter to continue...)
---

 Playing the Game
Playing the Game: 100%|██████████████████████████████████████ [time left: 00:00]
Playing the Game completed successfully!

---
(Press Enter to continue...)
---

"That was fun!" Eibhilin exclaims, "I found the flag!"

---
(Press Enter to continue...)
---

Nyx says, "Great job, Ei! I've read that a lot of players create writeups of
interesting challenges they solve during the competition. Just be sure to wait
to publish them until after the winners have been announced. We can work on
that together if you'd like."

---
(Press Enter to continue...)
---

"Thanks, Nyx! Here's the flag I found: picoCTF{m1113n1um_3d1710n_219b5811}"

---
(Press Enter to continue...)
---

"Great, you just got 10 points!" Nyx exclaims.

---
(Press Enter to continue...)
---

Eibhilin smiles, "I'm off to a good start!"

---
(Press Enter to continue...)
---
```
** picoCTF flag**
```bash
picoCTF{m1113n1um_3d1710n_219b5811}
```
