# [에러 처리](https://www.youtube.com/playlist?list=PLogzC_RPf25HEhe3ppTA_gWglxa853jgd)

### [P101. SunCertPathBuilderException](https://youtu.be/obbhEkm6cgs)
#### STS에서 Spring Boot 프로젝트 만들 때 나는 에러 
# <hr>

### [P102.  could not find a version that satisfies the requirement](https://youtu.be/SvFBGJaGWeY)
#### 파이참(파이썬)에서 패키지 임포트 할 때 나는 에러
# <hr>

### [P103.  get http://%2f%2f.%2fpipe%2fdocker_engine/v1.40/containers/json](https://youtu.be/gg4copHAtVQ)
#### 윈도우에 도커에 설치하고 나서 구동할 때 나는 에러
# <hr>


### [P104. VMware Player and Device/Credential Guard are not compatible](https://youtu.be/KNXTi0TkQk8)
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