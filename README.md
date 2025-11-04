# -cibersecurity-desafio-phishing
DIO BootCamp -  cibersecurity-desafio-phishing

cat > Phishing.md <<'EOF'
# Phishing — Relatório do Exercício (SEToolkit)

## Sumário
- Ferramenta: Social-Engineering Toolkit (SET)
- Modo: Credential Harvester → Site Cloner
- Ambiente: Kali Linux (VM VirtualBox)
- URL alvo (clonado no laboratório): http://www.facebook.com
- IP para POST back (lab): 192.xxx.x.xxx

---

## 1. Procedimento Executado

Setoolkit
- 1) Social-Engineering Attacks
  - 2) Website Attack Vectors
    - 3) Credential Harvester Attack Method
      - 2) Site Cloner
      - set:webattack> IP address for the POST back in Harvester/Tabnabbing [192.***.0.***]: 
      - [-] SET supports both HTTP and HTTPS
        [-] Example: http://www.thisisafakesite.com
        set:webattack> Enter the url to clone: http://www.facebook.com




<img width="567" height="319" alt="image" src="https://github.com/user-attachments/assets/8883934b-ce52-45e5-bd9f-ba64d83c3dcb" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/3e647cc1-6e9a-4f5b-aec1-4d7c0898b921" />

<img width="567" height="319" alt="image" src="https://github.com/user-attachments/assets/01af8361-8cd9-4d05-aeb8-79475df77b0d" />

<img width="567" height="319" alt="image" src="https://github.com/user-attachments/assets/dde6892b-875c-4328-9ec2-5d589f4fa4dd" />


Relatório:

<harvester>
login.facebook.com/login.php
<url>
<param>------WebKitFormBoundary0CAnMjDBGpLeXtls</param>
</url>
<url>
<param>local_storage[signal_flush_timestamp]=13</param>
<param>local_storage[Session]=20</param>
<param>local_storage[hb_timestamp]=13</param>
<param>local_storage[banzai:last_storage_flush]=18</param>
<param>session_storage[sp_pi]=216</param>
<param>session_storage[TabId]=6</param>
<param>logtime=0</param>
<param>__aaid=0</param>
<param>__user=0</param>
<param>__a=1</param>
<param>__req=2</param>
<param>__hs=20396.BP:DEFAULT.2.0...0</param>
<param>dpr=2</param>
<param>__ccg=EXCELLENT</param>
<param>__rev=1029362725</param>
<param>__s=8v3pel:o6tmps:x4d5kn</param>
<param>__hsi=7568865568772464419</param>
<param>
__dyn=7xe6E5aQ1PyUbFp41twpUnwgU29zE6u7E3rw5ux609vCwjE1EE2Cw8G1Qw5Mx61vw5zwqo1nE1u83mwaS0zK1sw2oEG0hi0Lo6-0uS0ue0QU3yw
</param>
<param>__hsdp=gIMX1-VUt_a3AM2ow</param>
<param>
__hblp=0Vwbq12w2jU1Bo7y0bUw57w3EE3Lw08N25U0lnyto423y7F-07ME
</param>
<param>lsd=AdEmelkpO9U</param>
<param>jazoest=2992</param>
<param>__spin_r=1029362725</param>
<param>__spin_b=trunk</param>
<param>__spin_t=1762263842</param>
</url>
<url>
<param>local_storage[signal_flush_timestamp]=13</param>
<param>local_storage[Session]=20</param>
<param>local_storage[hb_timestamp]=13</param>
<param>local_storage[banzai:last_storage_flush]=18</param>
<param>session_storage[sp_pi]=216</param>
<param>session_storage[TabId]=6</param>
<param>logtime=0</param>
<param>__aaid=0</param>
<param>__user=0</param>
<param>__a=1</param>
<param>__req=3</param>
<param>__hs=20396.BP:DEFAULT.2.0...0</param>
<param>dpr=2</param>
<param>__ccg=EXCELLENT</param>
<param>__rev=1029362725</param>
<param>__s=:o6tmps:x4d5kn</param>
<param>__hsi=7568865568772464419</param>
<param>
__dyn=7xe6E5aQ1PyUbFp41twpUnwgU29zE6u7E3rw5ux609vCwjE1EE2Cw8G1Qw5Mx61vw5zwqo1nE1u83mwaS0zK1sw2oEG0hi0Lo6-0uS0ue0QU3yw
</param>
<param>__hsdp=gIMX1-VUt_a3AM2ow</param>
<param>
__hblp=0Vwbq12w2jU1Bo7y0bUw57w3EE3Lw08N25U0lnyto423y7F-07ME
</param>
<param>lsd=AdEmelkpO9U</param>
<param>jazoest=2992</param>
<param>__spin_r=1029362725</param>
<param>__spin_b=trunk</param>
<param>__spin_t=1762263842</param>
</url>
<url>
<param>------WebKitFormBoundaryHk3yiAi41UHrAwta</param>
</url>
<url>
<param>------WebKitFormBoundaryQk88c6y5ZOGRpvGl</param>
</url>
<url>
<param>------WebKitFormBoundaryIcAUN412pzQ2BQx5</param>
</url>
<url>
<param>------WebKitFormBoundaryCBY7nndhY3QTjcFZ</param>
</url>
<url>
<param>------WebKitFormBoundaryWA1GACZ1ADIYDPVZ</param>
</url>
<url>
<param>------WebKitFormBoundaryMuViVxem2LIm2qi4</param>
</url>
<url>
<param>------WebKitFormBoundaryMSDf9BLP28bbTa51</param>
</url>
<url>
<param>------WebKitFormBoundaryG58lhvwXB04xRWgp</param>
</url>
<url>
<param>------WebKitFormBoundaryUwa8magIWT8DXMAR</param>
</url>
<url>
<param>local_storage[signal_flush_timestamp]=13</param>
<param>local_storage[Session]=20</param>
<param>local_storage[hb_timestamp]=13</param>
<param>local_storage[banzai:last_storage_flush]=18</param>
<param>session_storage[sp_pi]=216</param>
<param>session_storage[TabId]=6</param>
<param>logtime=0</param>
<param>__aaid=0</param>
<param>__user=0</param>
<param>__a=1</param>
<param>__req=4</param>
<param>__hs=20396.BP:DEFAULT.2.0...0</param>
<param>dpr=2</param>
<param>__ccg=EXCELLENT</param>
<param>__rev=1029362725</param>
<param>__s=fvb53j:o6tmps:vor21y</param>
<param>__hsi=7568865568772464419</param>
<param>
__dyn=7xe6E5aQ1PyUbFp41twpUnwgU29zE6u7E3rw5ux609vCwjE1EE2Cw8G1Qw5Mx61vw5zwqo1nE1u83mwaS0zK1sw2oEG0hi0Lo6-0uS0ue0QU3yw
</param>
<param>__hsdp=gIMX1-VUt_a3AM2ow</param>
<param>
__hblp=0Vwbq12w2jU1Bo7y0bUw57w3EE3Lw08N25U0lnyto423y7F-07ME
</param>
<param>lsd=AdEmelkpO9U</param>
<param>jazoest=2992</param>
<param>__spin_r=1029362725</param>
<param>__spin_b=trunk</param>
<param>__spin_t=1762263842</param>
</url>
<url>
<param>------WebKitFormBoundaryRKLYLVzePFUEZvGB</param>
</url>
<url>
<param>local_storage[signal_flush_timestamp]=13</param>
<param>local_storage[Session]=20</param>
<param>local_storage[hb_timestamp]=13</param>
<param>local_storage[banzai:last_storage_flush]=18</param>
<param>session_storage[sp_pi]=216</param>
<param>session_storage[TabId]=6</param>
<param>logtime=0</param>
<param>__aaid=0</param>
<param>__user=0</param>
<param>__a=1</param>
<param>__req=6</param>
<param>__hs=20396.BP:DEFAULT.2.0...0</param>
<param>dpr=2</param>
<param>__ccg=EXCELLENT</param>
<param>__rev=1029362725</param>
<param>__s=:o6tmps:vor21y</param>
<param>__hsi=7568865568772464419</param>
<param>
__dyn=7xe6E5aQ1PyUbFp41twpUnwgU29zE6u7E3rw5ux609vCwjE1EE2Cw8G1Qw5Mx61vw5zwqo1nE1u83mwaS0zK1sw2oEG0hi0Lo6-0uS0ue0QU3yw
</param>
<param>__hsdp=gIMX1-VUt_a3AM2ow</param>
<param>
__hblp=0Vwbq12w2jU1Bo7y0bUw57w3EE3Lw08N25U0lnyto423y7F-07ME
</param>
<param>lsd=AdEmelkpO9U</param>
<param>jazoest=2992</param>
<param>__spin_r=1029362725</param>
<param>__spin_b=trunk</param>
<param>__spin_t=1762263842</param>
</url>
<url>
<param>------WebKitFormBoundaryuCLAt8oBLyUWz8RX</param>
</url>
</harvester>


