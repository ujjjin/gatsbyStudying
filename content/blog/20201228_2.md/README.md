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
### 내 블로그 수정하기 첫번째
>> PS C:\dev_folder\workspace\SKProject> cd C:\Users\USER\201211\201211
>> PS C:\Users\USER\201211\201211> code .

**code . 란 새로운 Visual Studio Code창을 띄워 현재 레포지토리 작업을 실행하겠다는..!**

### "git" in TERMINER
 동작하고 있는지 확인하라
 + 터미널 안에서의 패스워드 입력은 항상 보이지않는다 그만 두드려라

### 왜 로그인이 안될까  
>> PS C:\Users\USER\201211\201211> git push --set-upstream orig
>> Logon failed, use ctrl+c to cancel basic credential prompt.
>> Username for 'https://github.com': zzzz0600@gmail.com
>> Password for 'https://zzzz0600@gmail.c@github.com':
>> remote: Invalid username or password.
>> fatal: Authentication failed for 'https://github.com/ujjjin/

### 검색해보니, 업데이트 !
>> PS C:\Users\USER\201211\201211> git update
>> Warning! `git update` has been deprecated;
>> Git for Windows 2.27.0.windows.1 (64bit)
>> Download and install Git for Windows v2.29.2(3) [N/y]? y
>>########################################################################################################################

## 그러고나니, 업데이트 된 깃에는 PULL되어있지 않았기에 한번더 오류!
>> PS C:\Users\USER\201211\201211> git push
>> fatal: The current branch main has no upstream branch.
>> To push the current branch and set the remote as upstream, u
>>
>>    git push --set-upstream origin main
>> fatal: : The term 'fatal:' is not recognized as the name of 
>> a cmdlet, function, script file, or operable program. Check 
>> the spelling of the name, or if a path was i
>> ncluded, verify that the path is correct and try again.     
>> At line:1 char:1
>> + fatal: The current branch main has no upstream branch.    
>> + ~~~~~~
>>    + CategoryInfo          : ObjectNotFound: (fatal::String) [], CommandNotFoundException
>>    + FullyQualifiedErrorId : CommandNotFoundException      

## 근데 사실 잘모르겠음. 그래서 SOURCETREE 다운받음.
내가 작업중인 파일을 드래그해서 가져다 놓으면 해당 파일을 소스트리가 읽는다. 

그리고, 이렇게 내용을 수정이나 추가, 변경 후 좌측 세번째..버튼을 클릭하면 내가 COMMIT-PUSH 이후의 수정작업내용을 확인할 수 있다.
메시지란에 수정내용에 대해 간단한 메모를 한다.(이후 소스코드에서 수정내용타이틀을 확인 할 수 있기에 간편히 인지 가능)
SOURCETREE에서 main or history를 확인하여 PUSH하면 내 블로그에 업데이트가 가능하다.

