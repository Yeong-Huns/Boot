![[Sync_1.png]]

>[!tip]
>1. 왼쪽 하단의 `톱니바퀴` 모양을 눌러서 `설정`-> `GitHub Sync` 로 이동한다.

![[Sync_2.png]]

>[!tip]
>1. ==GitHub username== 
>>* 깃허브 계정을 입력한다.
>    
><br>
>
>2. ==GitHub personal access token==
>>[!abstract]- 깃허브 토큰 발급
>>![[GitHub1.png]] 
>>> 1. 깃허브에 접속하여 우측의 `GitHub` - `Setting` 에 들어간다.
>>
>>![[GitHub2.png]]
>>> 2.  좌측의 하단의 `Developer Setting`을 누른다.
>>
>>![[GitHub3.png]]
>>> 3. `Token (classic)` 을 눌러서 토큰을 발급받는다.
> * 발급받은 토큰 주소를 입력한다.
><br>
>
> 3. ==GitHub repo URL for this vault== 
>> * 깃허브 레포지토리 주소를 입력한다.
>   
><br>
>
> 4. ==git binary location (optional)==
>* 만약 `git.exe`를 찾지 못한다는 오류가 발생할 경우, ==아래== 내용을 참조하여 
>`git.exe` 주소를  입력해준다.
>>[!abstract]- `git.exe` 위치
>>If you're using [GitHub for Windows](https://desktop.github.com/), git.exe may not be in your PATH, but you may find it in a location like: `C:\Users\<username>\AppData\Local\GitHub\PortableGit_<numbersandletters>\bin\git.exe`
>>
>>That's the situation for me, in Windows 7 + version 1.0 of GitHub for Windows.
>>
>>In Windows 10 it appears to be in:
>>
>>`C:\Users\<username>\AppData\Local\GitHub\PortableGit_<numbersandletters>\cmd\git.exe`
>>
>>( \cmd versus \bin)
>>
>>**From [GitHub Desktop](https://desktop.github.com/) 1.1**
>>
>>The UI is different and the Git path now is in:
>>
>>`C:\Users\<username>\AppData\Local\GitHubDesktop\app-<appversion>\resources\app\git\cmd\git.exe`
>>
>>**PS:** _AppData_ is a hidden folder by default.    
>
><br>
>
> 5. ==Auto Sync at interval (optional)==
>>* `몇 분` 간격으로 동기화를 진행할 지 설정한다. 
>  `0`이나 `음수(-)`일 경우, 동기화를 진행하지 않는다. 
>  또한, 적용을 위해 `Obsidian` 재시작이 필요하다.

   