# [에러 처리](https://www.youtube.com/playlist?list=PLogzC_RPf25HEhe3ppTA_gWglxa853jgd)

### [SunCertPathBuilderException](https://youtu.be/obbhEkm6cgs)
#### STS에서 Spring Boot 프로젝트 만들 때 나는 에러 
# <hr>

### [could not find a version that satisfies the requirement](https://youtu.be/SvFBGJaGWeY)
#### 파이참(파이썬)에서 패키지 임포트 할 때 나는 에러
# <hr>

### [get http://%2f%2f.%2fpipe%2fdocker_engine/v1.40/containers/json](https://youtu.be/gg4copHAtVQ)
#### 윈도우에 도커를 설치하고 나서 구동할 때 나는 에러 (feat. 응 윈도우는 아니야~)
# <hr>


### [VMware Player and Device/Credential Guard are not compatible](https://youtu.be/KNXTi0TkQk8)
#### vmware iso 파일 구동 안될 때 
```
mountvol X: /s
copy %WINDIR%\System32\SecConfig.efi X:\EFI\Microsoft\Boot\SecConfig.efi /Y
bcdedit /create {0cb3b571-2f2e-4343-a879-d86a476d7215} /d "DebugTool" /application osloader
bcdedit /set {0cb3b571-2f2e-4343-a879-d86a476d7215} path "\EFI\Microsoft\Boot\SecConfig.efi"
bcdedit /set {bootmgr} bootsequence {0cb3b571-2f2e-4343-a879-d86a476d7215}
bcdedit /set {0cb3b571-2f2e-4343-a879-d86a476d7215} loadoptions DISABLE-LSA-ISO,DISABLE-VBS
bcdedit /set {0cb3b571-2f2e-4343-a879-d86a476d7215} device partition=X:
mountvol X: /d
bcdedit /set hypervisorlaunchtype off
```
# <hr>

### [no matching manifest for windows/amd64 in the manifest list entries](https://youtu.be/CtFWWzMAqg0)
#### 윈도우 도커에 이미지 가져올 때 나는 에러 (feat. 응 윈도우는 아니야~)
# <hr>

### [CentOS8 docker 설치](https://youtu.be/wd5EdxRjlME)
#### 공식 사이트 참고하여 CentOS8에 docker 설치
#### 설치 시 나오는 에러 처리하기
#### 서비스로 등록하기
#### httpd 설치하고 서비스 테스트 하기
# <hr>

### [VMWare에 CentOS8 설치](https://youtu.be/EK_M-m1ZnMs)
#### CentOS8 네트워크 잡기
#### CentOS8 사용자 만들기
#### CentOS8 사용자 sudo 권한 주기
#### root 쓰지 말라는 잔소리
# <hr>

### [Docker registry Viewer](https://youtu.be/TDGW0c5wmV8)
#### 1. Make Docker registry 
#### 2. Insert image & tag at Docker registry
#### 3. Check image & tag by CURL command
#### 4. Make Docker registry View 
#### 5. Check image & tag by Web
#### 6. Introduce regiview at Docker hub
##### https://hub.docker.com/repository/docker/parkseungchul/regiview
# <hr>

### [P108. 야 나두 centos7(feat. 윈도우 이제 그만~)](https://youtu.be/r6tuoqK-hhs)
#### 1. VMware Download 
#### 2. CentOS7 Download 
#### 3. VMware Install
#### 4. CentOS7 Install 
#### 5. CentOS7 IP set
#### 6. VMware IP set
#### 7. Connect SSH 
# <hr>

### [P109. Spring Boot DockerFile 만들기(feat. 아주 이쁘게)]()
#### Centos8에서
#### Git 잘 구슬려서 
#### Spring Boot 소스를 가져 오구오구
#### Maven 빌드도 하궁
#### Asia/Seoul 시간대로 옵션을 주고 맞춰써
#### DockerFile을 만들엌
#### 환경변수로 C.UTF-8을 줘서 한글도 잘 나오넹?
#### 결론적으로 이쁘게 Spring Boot Container 구동!!!
# <hr>