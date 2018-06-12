[vsCodeStartupCs]: img/vsCodeStartupCs.png " "
[vsCodeFortuneControllerCs]: img/vsCodeFortuneControllerCs.png " "
[vsCodeFortuneCs]: img/vsCodeFortuneCs.png " "



# Lab 01 - Clone Source and Push Apps

## Clone Source (Java/Spring)

1. Download the Java app  by cloning Git Repo or download the zip
```

> git clone https://github.com/pivotal-education/pcf-articulate-code 

```
## Push The Java/Spring App
1. Open command prompt and navigate to the app directory.
```
> cd ./pcf-articulate-code
```
2. Confirm the API target is set
```
> cf target

API endpoint:   <PROVIDED_BY_INSTRUCTOR>
User:           <STUDENT-X>
Org:            West
Space:          <STUDENT-X>
```
3. Push the app
```
> cf push <javaSpringAppName>-studentX 
```

4. The cf cli will provide feedback about each step it takes to create the App Container and deploy.

## View The Java/Spring App
1. Verify your app in the apps manager
2. Question: What buildpack does it use?

## Clone Source (.NET/.NET Core - skip this section if you are a Java/Spring shop)

1. Download the .NET app source code, by cloning Git Repo or download the zip
```

> git clone https://github.com/jennymclaughlin/DotNetAttendees

```
2. Download the .NET Core app source code, by cloning Git Repo or download the zip
```

> git clone https://github.com/jennymclaughlin/dotnetcoreCFdemo

```
## Push The .NET App (skip this section and the next section if you are a Java/Spring shop)
1. Unzip pcf-asp.net-mvc-attendees.zip, open command prompt and navigate to the app directory.
```
> cd ~\pcf-asp.net-mvc-attendees\pcf-asp.net-mvc-attendees\PivotalWorkshop
```
2. Confirm the API target is set
```
> cf target

API endpoint:   <PROVIDED_BY_INSTRUCTOR>
User:           <STUDENT-X>
Org:            West
Space:          <STUDENT-X>
```
3. Push the app
```
> cf push <dotnetappName>-studentX -s windows2012R2 
```
4. The cf cli will provide feedback about each step it takes to create the App Container and deploy.

## View The .NET App
1. Verify your app in the apps manager
2. Question: What buildpack does it use?

## Push The .NET Core App
1. Open command prompt and navigate to the app directory.
```
> cd ~\dotnetcoreCFdemo
```
2. Confirm the API target is set
```
> cf target

API endpoint:   <PROVIDED_BY_INSTRUCTOR>
User:           <STUDENT-X>
Org:            West
Space:          <STUDENT-X>
```
3. Push the app
```
> cf push <dotnetCoreappName>-studentX 
```
** No need to specifiy the windows stack

4. The cf cli will provide feedback about each step it takes to create the App Container and deploy.

## View The .NET Core App
1. Verify your app in the apps manager
2. Question: What buildpack does it use?


___

___
| **[Prev Lab](../AppMgr-Login/README.md)** |_______________________________________________________________________________| **[Next Lab](../Lab-02/README.md)** |
