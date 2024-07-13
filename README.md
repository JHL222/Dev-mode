<div align="center">
   
# 하이퍼레저 패브릭을 이용한 음원 거래 플랫폼

# 1-1. 개발기간

2024.06.22 ~ 06.23 프로젝트 기획 <br/>
2024.06.24 기능 및 역할 정의 <br/>
2024.06.25 ~ 06.27 체인코드 설계 <br/>
2024.06.28 백엔드 연동 <br/>
2024.06.29 프론트엔드 연동 <br/>

***

# 1-2. 개발목적

블록체인 기술을 활용하여 음원 제작자와 소비자 간의 직접적이고 안전한 거래를 지원하는 플랫폼을 개발하는 것을 목표로 합니다. <br/>
기존의 음원 시장에서는 중개자가 개입되어 있는 경우가 많아 거래 과정에서의 투명성과 안전성이 부족할 수 있습니다. <br/>
이러한 문제를 해결하기 위해 블록체인을 활용하여 거래 과정을 분산화하고 보안성을 강화할 계획입니다. <br/>
   
***

# 2-1. 개발환경

### Environment

<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=Linux&logoColor=white"/>

### IDE
<img src="https://img.shields.io/badge/Visual&nbsp;Studio&nbsp;Code-007ACC?style=flat-square&logo=VisualStudioCode&logoColor=white"/>

### 형상관리

<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=Git&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white"/><br/>

### Development

<img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=Express&logoColor=white"/>
<img src="https://img.shields.io/badge/Angular-0F0F11?style=flat-square&logo=Angular&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=JavaScript&logoColor=white"/>

***

# 2-2. 버전

cURL <br/>
도커Docker Community Edition CE 23.0.6 <br/>
도커 Compose 1.27.4<br/>
Go 1.16.7 <br/>
Python 2.7.18 <br/>
Node.js 12.13.1 <br/>
npm 5.6.0 <br/>

# 2-3. 환경 설정
</div>

```
git clone https://github.com/JHL222/dev-mode.git
```
```
cd $GOPATH/src/dev-mode
cp -r ../fabric-samples/bin/ .
```
```
./network.sh start
```
```
cd $GOPATH/src/dev-mode
./network.sh installCC abstore
./network.sh checkCC
./network.sh upgradeCC abstore 1.1.0
```
```
./network.sh startSDK
```

<div align="center">

# 2-4. 시연 영상

https://youtu.be/4wOM_sk6Bno

# 3. 결과 보고서
[하이퍼레저 패브릭을 이용한 음원거래 플랫폼 프로젝트 결과 보고서.pptx](https://github.com/user-attachments/files/16200523/default.pptx)

***

# 4. 주요 기능

∙음원 등록 기능 <br/>
∙음원 조회 기능 <br/>
∙회원가입 / 로그인 기능 <br/>
∙음원 거래 기능 <br/>
∙회원가입 시 1000포인트 지급, 하루에 1번 로그인 시 100포인트 지급<br/>
∙음원 등록 시 등록 금액의 2% 수수료, 음원 판매 시 5% 수수료, 음원 구매 시 5% 적립금 지급<br/>


</div>
