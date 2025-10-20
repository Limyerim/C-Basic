# CShrap-Basic

## 1. 경로 찾기 

- 현재 프로젝트 경로 
```
System.IO.Directory.GetParent(Environment.CurrentDirectory).Parent.FullName
```

- 현재 솔루션 경로
```
System.Reflection.Assembly.GetEntryAssembly().GetName().Name
```

- 현재 실행되는 프로그램 경로
```
System.AppDomain.CurrentDomain.BaseDirectory
```
