## Introduction

This adds a permanent notification that looks like the following:

![image](https://user-images.githubusercontent.com/98544186/195166547-7f06da3e-92fc-4c28-b726-9e086566e1d1.png)


**File:** [notification2-echostretch.db](https://github.com/crump-youtube/PS5_JB_Archive/blob/main/PS5_Notifications/notification2-echostretch.db) or the one that points to my [notification2.db](https://github.com/crump-youtube/PS5_JB_Archive/blob/main/PS5_Notifications/notification2.db)

**Location:** /system_data/priv/mms

**Notes:** File should be named notification2.db

![image](https://user-images.githubusercontent.com/98544186/195154810-37e26956-eaa7-409d-88aa-59aff3f3b501.png)


**File:** [setting.png](https://github.com/crump-youtube/PS5_JB_Archive/blob/main/PS5_Notifications/setting.png)

**Location:** /user/data/notifi

**Notes:** You'll need to create the `notifi` directory before adding the Image.

![image](https://user-images.githubusercontent.com/98544186/195164693-64f2d6ae-88a4-40fe-a27d-35f556406374.png)

## Videos for the PS5 Kernel Exploit (4.03/4.50/4.51)

Checkout my [playlist](https://www.youtube.com/playlist?list=PL3Q83485j_tVTBhXkqZBmpo0tmFhQvpv0) for all of my content on the PS5 Kernel exploit so far! 

While you are there, you might also want to [<img src="https://img.shields.io/badge/-Subscribe-red?style=for-the-badge&logo=youtube&logoColor=white"/>](https://www.youtube.com/c/mbcrump?sub_confirmation=1) to my channel to keep up to date with the latest and the greatest. 

## Extra Info

The `raw_data` that makes up a notification:

```json
{
   "bundleName":"download",
   "channelType":"ServiceError",
   "isAnonymous":true,
   "isImmediate":false,
   "priority":1,
   "toastOverwriteType":"No",
   "useCaseId":"NUC259",
   "viewData":{
      "actions":[
         {
            "actionName":"⭐Activate Webkit",
            "actionType":"DeepLink",
            "defaultFocus":true,
            "parameters":{
               "actionUrl":"http://crump-youtube.github.io/"
            }
         },
         {
            "actionName":"⭐Activate URL Redirector",
            "actionType":"DeepLink",
            "defaultFocus":true,
            "parameters":{
               "actionUrl":"https://ithaqua.exploit.menu/"
            }
         },
         {
            "actionName":"⭐Activate Google",
            "actionType":"DeepLink",
            "defaultFocus":true,
            "parameters":{
               "actionUrl":"https://www.google.com/"
            }
         }
     
      ],
      "icon":{
         "parameters":{
            "url":"\/user\/data\/notifi\/setting.png"
         },
         "type":"Url"
      },
      "message":{
         "body":"★Debug menu"
      },
      "subMessage":{
         "body":""
      }
   },
   "viewTemplateType":"InteractiveToastTemplateB"
}

```

## Credit

Credit goes to [Jose Gonzalez](https://twitter.com/josegar21481364) for exploring and creating the original notification2.db file. 
