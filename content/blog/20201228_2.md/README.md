---
title: read me
date: "2020-12-28T08:10:03.284Z"
description: "습작 새벽기상의 시작과 기록 1"
categories: [헬로 월드~~]
comments: true
image:
  feature: https://images.unsplash.com/photo-1440635592348-167b1b30296f?crop=entropy&dpr=2&fit=crop&fm=jpg&h=475&ixjsv=2.1.0&ixlib=rb-0.3.5&q=50&w=1250
  credit: thomas shellberg
  creditlink: https://unsplash.com/photos/Ki0dpxd3LGc
---
## 1. 내 블로그 수정하기 첫번째
>> PS C:\dev_folder\workspace\SKProject> cd C:\Users\USER\201211\201211 <br>
>> PS C:\Users\USER\201211\201211> code .
**code . 란 새로운 Visual Studio Code창을 띄워 현재 레포지토리 작업을 실행하겠다는..!**

## 2. "git" in TERMINER
 + 동작하고 있는지 확인하라
 + 터미널 안에서의 패스워드 입력은 항상 보이지않는다 그만 두드려라

## 3. 왜 로그인이 안될까  
>> PS C:\Users\USER\201211\201211> git push --set-upstream orign <br>
>> Logon failed, use ctrl+c to cancel basic credential prompt. <br>
>> Username for 'https://github.com': zzzz0600@gmail.com <br>
>> Password for 'https://zzzz0600@gmail.c@github.com': <br>
>> remote: Invalid username or password. <br>
>> fatal: Authentication failed for 'https://github.com/ujjjin/ <br>

## 4. 검색해보니, 업데이트 !
>> PS C:\Users\USER\201211\201211> git update <br>
>> Warning! `git update` has been deprecated; <br>
>> Git for Windows 2.27.0.windows.1 (64bit) <br>
>> Download and install Git for Windows v2.29.2(3) [N/y]? y <br>
>>########################################################################################################################

## 5. 그러고나니, 업데이트 된 깃에는 PULL되어있지 않았기에 한번더 오류!
>> PS C:\Users\USER\201211\201211> git push <br>
>> fatal: The current branch main has no upstream branch.<br>
>> To push the current branch and set the remote as upstream, u <br> <br>
>>
>>    git push --set-upstream origin main <br>
>> fatal: : The term 'fatal:' is not recognized as the name of <br>
>> a cmdlet, function, script file, or operable program. Check <br>
>> the spelling of the name, or if a path was i <br>
>> ncluded, verify that the path is correct and try again. <br>     
>> At line:1 char:1 <br>
>> + fatal: The current branch main has no upstream branch.   <br>
>> + "~~~~~" <br>
>>    + CategoryInfo          : ObjectNotFound: (fatal::String) [], CommandNotFoundException <br>
>>    + FullyQualifiedErrorId : CommandNotFoundException       <br>

## 근데 사실 잘모르겠음. 그래서 SOURCETREE 다운받음.
+ 내가 작업중인 파일을 드래그해서 가져다 놓으면 해당 파일을 소스트리가 읽는다. 

+ 그리고, 이렇게 내용을 수정이나 추가, 변경 후 좌측 세번째..버튼을 클릭하면 내가 COMMIT-PUSH 이후의 수정작업내용을 확인할 수 있다.
메시지란에 수정내용에 대해 간단한 메모를 한다.(이후 소스코드에서 수정내용타이틀을 확인 할 수 있기에 간편히 인지 가능)
SOURCETREE에서 main or history를 확인하여 PUSH하면 내 블로그에 업데이트가 가능하다.



추가 메시지. 
인용주석?으로 달은 글자들 사이즈 변경하는 방법 알아보기
