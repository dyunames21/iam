
# 클라우드 네이티브 IAM(Identity and Access Management) 솔루션

한이음 프로젝트 
팀원 : 박진형, 전우재, 박채림, 정지현  


## Overview
클라우드 컴퓨팅 환경에 적용이 가능한 IAM 시스템을 설계하고 구현하는 프로젝트이다. 계정 및 권한관리, 모니터링 등을 바탕으로 기업내 다양한 시스템의 접근 통합 관리 보안 솔루션을 구현하는 것이 목표

## 솔루션 제안 배경
 Covid-19 이후 클라우드 컴퓨팅 시장은 급격한 성장세를 보이고 있다. 이에 구글(Google), 마이크로소프트(MS), IBM, 아마존(Amazon) 등 대표적인 IT 기업들은 이를 차세대 핵심 비즈니스로꼽고 SaaS(Software as a Service), PaaS(Platform as aService), IaaS(Infrastructure as a Service) 등 다양한 클라우드 컴퓨팅서비스 및 제품들을 출시하고 있다.

그러나 이러한 발전의 이면에는 늘 클라우드 컴퓨팅 7가지 보안 위협 (클라우드 컴퓨팅 남용 및 오용, 불안정한 환경 및응용 프로그램 환경, 악성코드 공격, 기술 인프라의 공유, 데이터 손실 및 유출, 계정 혹은 서비스 침해, 알려지지 않은 위험)이 공존하며 이외에도 끊임없는 보안 위협이 등장하고 있다.

이러한 상황에서클라우드 컴퓨팅의 리소스를 제어할 수 있는 인증과 접근 관리 체계가 아주 중요한 보안요소이다.

## 주요 기능
+ 인증 정책 관리 기능 : IAM 인증 정책을 관리하는 기능
+ 사용자 인증 기능 : 사용자의 인증정보를 확인하고 리소스 접근 권한을 제어
+ 통계 및 로그 관리 : 인증 로그를 조회하고 관리하는 기능
+ 데모 웹 애플리케이션 : 인증 솔루션을 테스트하기 위한 테스트 웹페이지 구축


## 적용 기술
 + Keycloak를 사용한ID 및 액세스 관리
 + Node.js, JavaScript, HTML5,Springboot 등을 사용한 테스트 웹 페이지
 + MariaDB 데이터베이스
 + Docker를 사용한배포 자동화 및 운영
 + AWS 클라우드 서버


## 달성 성과
 + 한국정보처리학회(22.11.04), 논문명 : 클라우드 네이티브 IAM(Identity and Access Management) 솔루션 게재   
 + 단순한 웹서버 환경이 아니라 클라우드 네이티브한 환경에 대해 공부 할 수 있는 계기가 되었음.
 + KeyCloak을 사용한 IAM 솔루션 제작 및 인증/권한 관리 이해 및 구현 진행
 + 팀 프로젝트 과정에서 필요한 CI/CD 환경 조성
